## Backup for Mac
1. `sudo xcodebuild -license`  
2. `xcode-select --install`  
3. `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`  
4. `brew doctor`  
5. `brew update`  
6. `brew install python`
7. `brew install ansible`
8. `echo 'export HOMEBREW_CASK_OPTS="--appdir=/Applications"' >> ~/.bash_profile`
9. `source ~/.bash_profile`
10. `HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts -vv localhost.yml`
