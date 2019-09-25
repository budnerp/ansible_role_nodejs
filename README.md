# Ansible role for Node.js 
Ansible role for Node.js installation for CentOS 7.

## What's inside?
- Node.js in v10.16.3
- NPM

##Interesting dirs and files 
   
## Tested on

## Installation
1. Navigate to Ansible's roles folder
2. Add the repo to git modules
    ```
    git submodule add https://github.com/budnerp/ansible_role_nodejs.git ansible_role_nodejs
    ```
3. Add the role to Ansible's playbook file
    ```    
    roles:
    [...]
        - ansible_role_nodejs
    [...]
    ```

## Other links

## TO DO
-[ ] add dependencies

## License
Copyright (c) We Are Interactive under the MIT license.