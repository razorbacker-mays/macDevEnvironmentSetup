# Macbook Development Environment Setup
Notes on development environment setup on Macbook Pro

<br>

## React Native - Development Environment Setup
- Xcode
  - Installed thru the App Store
  - Command Line tools installed based upon preferences in Xcode
  - iOS simulator within Xcode
- NodeJs
  - installed using Homebrew 
    - ```brew install node```
- WatchMan
  - installed using Homebrew
    - ```brew install watchman```
- Ruby
  - Ruby version manager
    - **rbenv** selected as the Ruby version manager (https://github.com/rbenv/rbenv)
      - installed using Homebrew
        - ```brew install rbenv ruby-build```    
      - Load rbenv in your shell
        - run this and follow the printed instructions:
          - ```rbenv init```
          - ```# Load rbenv automatically by appending # the following to ~/.zshrc: eval "$(rbenv init - zsh)"```
  - Ruby installation
    - Installations for Ruby build environment
      - ```brew install openssl@1.1 readline libyaml gmp       export RUBY_CONFIGURE_OPTS="--with-openssl-dir=$(brew --prefix openssl@1.1)"```
    - Ruby version install of 2.7.6
      - ```rbenv install 2.7.6```
    - Activate the Ruby version with rbenv
      - ```rbenv global 2.7.6```
        -  Close terminal window and open a new one
        -  Verify the ruby version is now the version set by rbenv
          -  ```ruby --version```  
    - Install Bundler (https://bundler.io/)
      - ```gem install bundler```
    - Install CocoaPods (https://cocoapods.org/)
      - ```gem install cocoapods``` 
