# Macbook Development Environment Setup
Notes on development environment setup on Macbook Pro

<br>

## React Native - Development Environment Setup
- Xcode
  - Installed thru the App Store
  - Command Line tools installed based upon preferences in Xcode
- NodeJs
  - installed using Homebrew 
    - ```brew install node```
- WatchMan
  - installed using Homebrew
    - ```brew install watchman```
- Ruby
  - Ruby version manager
    - **rbenv** selected as the Ruby version manager
      - installed using Homebrew
        - ```brew install rbenv ruby-build```    
      - Load rbenv in your shell
        - run this and follow the printed instructions:
          - ```rbenv init```
          - ```# Load rbenv automatically by appending # the following to ~/.zshrc: eval "$(rbenv init - zsh)"```
  - Ruby installation
    - Installations for Ruby build environment
      - ```brew install openssl@1.1 readline libyaml gmp export RUBY_CONFIGURE_OPTS="--with-openssl-dir=$(brew --prefix openssl@1.1)"```
