### web Browser(Chrome)
### Text Editor(VsCode)
### Version Control(Git、Github、Mac/Linux - Terminal、Windows - Git Bash)
```
git config --global user.name "Your name here"
git config --global user.email "your_email@example.com"

git config --global core.editor "code --wait"

Check for SSH Key
ls ~/.ssh
Create an SSH Key
ssh-keygen -t ras -b 4096 -C "you_email@example.com"
Copy the SSH Key
Windows
  clip < ~/.ssh/id_ras_pub
Linux
  sudo apt-get install xclip
  xclip -sel clip < ~/.ssh/id_rsa.pub
Mac
  pbcopy < ~/.ssh/id_rsa.pub
```