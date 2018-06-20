# Install PHP formulas with homebrew openSSL and CURL

```
brew uninstall curl
brew install curl --with-openssl
brew link curl --force

brew tap vendidero/homebrew-vendidero-php

brew update
brew upgrade
brew cleanup

brew [re]install --build-from-source vendidero/vendidero-php/php@7.1
```

see https://github.com/Homebrew/homebrew-core/issues/27938