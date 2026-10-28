# CNIT-381
Weekly labs for CNIT 381

## Week 1
Created the repo, configured Git, cloned it, first commit.

## Week 2 
Practiced team Git collaboration with a partner: feature branches, pull 
requests, code review, and resolving a merge conflict on a shared network 
inventory site. 

Practiced team Git collaboration using VS Code and Git commands: feature 
branches, commits, pushes, pull requests, code review, squash merging, 
and resolving a merge conflict while building the UW-Stout CNIT 
Cybersecurity Technology Hub. 

## Week 3 
Containerized a duplicate-IP checker with Docker and published the image to Docker Hub. 

## Week 4 
Built a network config pipeline: an intent file plus a generator, containerized, 
with CI/CD that regenerates and validates the configs on every change. 

## Week 5 
Called the GitHub REST API from Python to read my repo and create an issue.

## Week 6: IP Plan Check Pipeline
**What I built:** A Python checker for our IP address plan, packaged in
Docker, run by GitHub Actions on every push, that opens a GitHub issue
through the API when the plan has errors.
**Repo:** https://github.com/tramnguyen105/ip-plan-check

## Week 8: OSPF by Hand, Then Automated 
What I did: configured OSPF manually, ran a provided playbook that automated it, 
and wrote my own playbook to back up the configs. What I learned: how ansible works, how to create an inventory file and yml file, I learned yml syntax as well as how to run an ansible-playbook.

## Week 9: Build a Network and Automate It End to End What I built: a CML topology (2 routers, a switch, and an Ubuntu control node), bootstrapped the devices by hand, then used Ansible to configure loopbacks, EIGRP, a login banner, and to back up all device. 
What I learned: I learned how to use Ansible inventory files and playbooks to automate network configurations across multiple devices. I also learned how to use different Ansible modules to configure, verify, and back up devices without entering commands manually on each one. This lab helped me understand how automation saves time, reduces configuration errors, and makes managing multiple network devices easier.
