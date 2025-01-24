# How to run 

```bash
ansible-playbook -i [path_inventory] [path_playbook]
```

# Role Directory Structure

This document explains the purpose and usage of the folders within a role structure.

## Directory Contents

1. **tasks**  
   Contains the main tasks that will be executed by the role.  

2. **handlers**  
   This folder includes files with specific actions or handlers triggered during configuration when necessary.  

3. **templates**  
   Contains file templates to be used by tasks or for creating dynamic configuration files based on variables.  

4. **files**  
   Stores files intended to be transferred to the target host.  

5. **vars**  
   Holds variables used by the roles. These variables can be referenced and accessed in the tasks of the roles.  

6. **default**  
   Contains the default variables for the roles. These variables can be modified as needed.  

7. **meta**  
   Stores metadata files about the role, including:  
   - Dependencies.  
   - Brief role description.  
   - Author and maintainer information.  

---

### Notes  
This structure ensures that roles are modular, reusable, and organized, following best practices for configuration management.