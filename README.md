# sw-child-theme

small stuff for my wp blog

## testing

If packagist is acting up be sure to
make sure it doesnt force https which makes it fail
add this to the composer.json

```
    "repositories": [
        {
            "type": "composer",
            "url": "https://packagist.org"
        },
        {
            "packagist": false
        }
    ],
```

- composer require-dev phpunit/phpunit:7.5
- composer require-dev lucatume/wp-browser:^2.2
- brew install selenium-server-standalone
- brew services start selenium-server-standalone
- brew cask install https://raw.githubusercontent.com/Homebrew/homebrew-cask/0d1e0888e1cc3365e96249d4f606eb293725f6b4/Casks/chromedriver.rb
- If Selenium isn't running properly, install Java SDK https://www.oracle.com/technetwork/java/javase/downloads/index.html
- Create a new db for acceptance tests, ex: newdbname_codeception
- Create a db dump and put it in tests/\_data
