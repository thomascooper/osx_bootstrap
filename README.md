Install homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
Install ansible
```
brew install ansible
```
Clone this repo
```
git clone https://github.com/thomascooper/osx_bootstrap.git
cd osx_bootstrap
```
Run this playbook
```
ansible-playbook setup.yml
```
