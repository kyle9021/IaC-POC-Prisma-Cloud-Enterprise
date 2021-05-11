# IaC-POC-Prisma-Cloud-Enterprise

## Assumptions

* You're using the ENTERPRISE EDITION OF PRISMA CLOUD
* You're using ubuntu 20.04
* You're able to reach your Prisma Cloud Enterprise Edition console from your ubuntu 20.04 machine
* You would know how to harden this process if working in a production environment.

## Instructions

* Step 1: `git clone https://github.com/Kyle9021/IaC-POC-Prisma-Cloud-Enterprise`
* Step 2: `cd IaC-POC-Prisma-Cloud-Enterprise/`
* Step 3: `nano iac_script.bash` and assign variables according to comment documentation
* Step 4: `nano config-file-template.json`and replace values within `<>` brackets
* Step 5: Install jq if you dont have it `sudo apt update && upgrade -y` then `sudo apt-get install jq` 
* Step 6: Install cowsay (optional) but recommended `sudo apt install cowsay`
* Step 5: `bash iac_script.bash`
