```
# Update git to at least git --version 2.10.0

$ git config user.name "InitialShape"

$ git config user.email "initialshape@protonmail.org

$ ssh-keygen -t rsa -b 4096 -C "initialshape@protonmail.com" -f $HOME/<project_name>/.ssh

$ vim .git/info/exclude
# add ".ssh/"

$ git config core.sshCommand "ssh -i ~/project_name>/.ssh/id_rsa"
```
