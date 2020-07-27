# Generate new ssh keys and integrate_ssh_keys_with_github account


ls -al ~/.ssh
git config --global user.name "username"
git config --global user.name
out put will be display your name  >>username

git config --global user.email "example@gmail.com"
git config --global user.email
then will show your email as like   >> example@gmail.com

git config --global --list
show all listed details of git accounts added as like below
  user.name=username
user.email=example@gmail.com

then   it will generate rsa file 
ssh-keygen -t rsa -b 4096 -C "example@gmail.com"

Enter file in which to save the key (/home/furqan/.ssh/id_rsa):   ["press enter button simply"]

ssh-add ~/.ssh/id_rsa

sudo apt-get install xclip

xclip -sel clip < ~/.ssh/id_rsa.pub

then open this file  name   .ssh/id_rsa.pub
 and copy keys from here and paste them into your inside new sshkey keys of github


 and enjoy
 
