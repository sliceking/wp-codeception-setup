# sw-child-theme

small stuff for my wp blog

## testing

add phpunit/phpunit:7.5 and lucatume/wp-browser:^2.2 as
dev dependencies. if packagist is acting up be sure to
make sure it doesnt force https which makes it fail

install selenium and chromedriver

- brew install selenium-server-standalone
- brew services start selenium-server-standalone
- brew cask install https://raw.githubusercontent.com/Homebrew/homebrew-cask/0d1e0888e1cc3365e96249d4f606eb293725f6b4/Casks/chromedriver.rb
