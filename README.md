# Publishing an API with IBM API Connect

## Install nvm

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

## Install apic

```
$ npm install -g apiconnect
```

## Sign into Bluemix and enable API Connect

1. Create a new Catalog and enable the Developer Portal

2. Create a new Product

3. Create a new API and associate API to Product

## Design the API

```
$ apic edit
```
