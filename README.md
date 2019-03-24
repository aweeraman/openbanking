# Install nvm

```
$ brew install nvm
$ mkdir ~/.nvm
```

Add the following to .bash_profile
```
export NVM_DIR="$HOME/.nvm"
[ -s "/usr/local/opt/nvm/nvm.sh" ] && . "/usr/local/opt/nvm/nvm.sh"  # This loads nvm
[ -s "/usr/local/opt/nvm/etc/bash_completion" ] && . "/usr/local/opt/nvm/etc/bash_completion"  # This loads nvm bash_completion
```

# Install apic

```
$ npm install -g apiconnect
```
