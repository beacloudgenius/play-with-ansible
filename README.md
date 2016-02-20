0. Clone this repo and cd into it

    git clone
1. Get a Digital Ocean droplet working with your id_rsa.pub
2. Grab its ip address
3. edit the `inventort/hosts` file and replace CHANGETHISPLEASE with the ip address
4. run ansible playbook

    ansible-playbook create_cloudgenius_user.yml
