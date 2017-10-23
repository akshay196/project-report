# Setup ManageIQ VM

2.1 Task description:
- Tried to install ManageIQ on local machine using developer setup
- But later we came to know that we can use ManageIQ appliance for environment. It requires 4 VCPU and minimum 8/10 GB of RAM to run ManageIQ properly in virtual machine

2.2 Challenges:
- Initially installed Fedora 26 as base operating system, but it had problems regarding nouveau graphic driver. Because of that it got freeze after login screen
- Then installed CentOS 7 and make it ready to use for project4
- While configuring ManageIQ VM  got the error at configuring database. It was not able to assign dedicated disk for database in ManageIQ. Instead, kept default database (/var/opt/rh/rh-postgresql 95/lib/pgsql) and will extend lvm when required

