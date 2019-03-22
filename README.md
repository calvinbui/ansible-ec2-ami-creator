# Ansible EC2 AMI Creator

1. Spins up an EC2 Spot instance/s
2. Runs roles on on those instances
3. Delete old AMI matching name
4. Creates new AMI from EC2 instances
4. Destroys EC2 instances

`AWS_PROFILE=ops ansible-playbook site.yml -vvv`