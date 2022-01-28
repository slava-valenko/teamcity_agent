Ansible Role: TeamCity Agent
=========
---
Installs TeamCity Agent on Debian/Ubuntu and Windows OS.

---
Requirements
---------
For Linux: requires JDK 8 to be installed.

For Windows: requires JDK 8 and Chocolatey to be installed.

---
Dependencies
---------
None.

---
Example Playbook
---------
```
- name: Create Teamcity Agent Windows
  hosts: teamcity_windows
  roles:
    - teamcity_agent
	
- name: Create Teamcity Agent Linux
  hosts: teamcity_linux
  roles:
    - teamcity_agent
```

---
License
---------
MIT (Expat) / BSD