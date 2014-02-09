apt-get install git or sudo apt-get -y install git-core
cd ~/.ssh
ls
ssh-keygen -t rsa -C "email@email.com"
vim id_rsa.pub
{{Copy the public key, paste it into your GitHub account SSH Key section}}
ssh -T git@github.com