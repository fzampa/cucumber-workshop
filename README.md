# Cucumber Hands-on

## Make sure you have these dependencies setup:

### Xcode Command Line Tools
`xcode-select --install`

### Homebrew
`ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"`


### rbenv
`brew update`
`brew install rbenv ruby-build`

`echo 'export RBENV_ROOT=/usr/local/var/rbenv' >> ~/.bashrc`
`echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bashrc`
`source ~/.bashrc`

# Setup Project
`git clone https://github.com/luhhsnunes/cucumber-workshop.git`
`cd cucumber-workshop`

`rbenv install`
`rbenv rehash`

`gem install bundler`
`bundle install`