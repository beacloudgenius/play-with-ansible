Clone this repo and cd into it

    git clone https://github.com/beacloudgenius/play-with-ansible.git
    cd play-with-ansible
    
Get a Digital Ocean droplet working with your `id_rsa.pub` and grab its `ip address`

Edit the `./inventory/hosts` file and replace `CHANGETHISPLEASE` with the `ip address` of your droplet

Run ansible playbook

    ansible-playbook create_cloudgenius_user.yml


Reference:

How to define host inventory?

    http://docs.ansible.com/ansible/intro_inventory.html
    
Playbook examples:

    https://github.com/ansible/ansible-examples

    
