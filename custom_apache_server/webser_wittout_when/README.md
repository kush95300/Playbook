# Task 14.3

## Description:

14.3 Create an Ansible Playbook which will dynamically
     load the variable file named same as OS_name and just by
     using the variable names we can Configure our target node.
     (Note: No need to use when keyword here.)


## Solution

<b> Task 14.3 Solution </b>

created playbook for this:

- webserver_without_when.yml : PLAYBOOK to install webserver without when keyword in playbook.
- remove_webservers.yml : PLAYBOOK to delete webserver without when keyword in playbook.
- Redhat-8.0.yml     :  CONTAINS Redhat related variable 
- Ubuntu-20.04.yml   :  CONTAINS Ubuntu related variables
- Amazon-2.yml   :  CONTAINS Amazon-linux related variables


<b>
Command : ansible-playbook webserver_without_when.yml 
</b>

#NOTE: System should have pip and ansible before running this playbook. 

Thank You 


CREATER: Kaushal Soni

