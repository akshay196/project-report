# Add OpenStack Provider in ManageIQ

3.1 Task description:
- Need to install OpenStack using Packstack and after installation, integrate that in ManageIQ

3.2 Challenges:
- Need to test installation of OpenStack with Packstack in VM
- Used CentOS cloud image but  didn't get password to login
- Then  used cloud-init to customized CentOS VM and successfully authenticate to CentOS VM
- While adding OpenStack provider in ManageIQ,  used Ceilometer or AMQP to receive events from OpenStack provider. It was not authenticating with OpenStack when used AMQP service
- Need to explore more about AMQP service validation to solve this issue
