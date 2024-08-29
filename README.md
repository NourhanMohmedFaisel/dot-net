git config --global user.name "NourhanMohmedFaisel"
git config --global user.email "mnourhan527@gmail.com"
ssh-keygen -t ed25519 -C "mnourhan527@gmail.com" 
git init
 git add index.html
 git commit -m "index added"
 git remote add origin git@github.com:NourhanMohmedFaisel/dot-net.git 
 git push origin master