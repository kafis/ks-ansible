# ANSIBLE

## Installation

### I have a cool beard and wear skinny jeans while drinking soja-latte during my pitch at Muschi Obermayer

    brew install ansible
    brew install https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb
    
### I have an impressive beard and listen to metal while I patch my Linux Kernel    
    
    apt-get install ansible 
    apt-get install ssh-pass
    
## Spin Up The Nodes

    cd nodes
    vagrant up
    
## Provision
    
    cd provisioning
    ansible-playbook -i environment/inventory site.yml
    
    