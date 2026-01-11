## Day 4 – SSH into EC2 Using Key Pair

### Objective
Securely access a cloud virtual machine using SSH key-based authentication.

### What I Did
- Generated and downloaded an EC2 key pair during instance launch
- Fixed SSH key permission issues using chmod
- Connected to the EC2 instance using SSH
- Verified successful login and cloud user identity

### Commands Used
- chmod 400 your-key.pem
- ssh -i your-key.pem user@public-ip
- whoami
- hostname

### Key Learnings
- Cloud VMs use key-based authentication instead of passwords
- Incorrect key permissions prevent SSH login
- Proper SSH access is a core cloud engineer responsibility

### Outcome
Successfully established secure SSH access to a cloud VM and resolved permission issues.
