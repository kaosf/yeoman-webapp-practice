# Yeoman webapp Practice

For getting started, refer [this repository](https://github.com/kaosf/yeoman-practice).

```sh
# run at only the first time
npm install -g yo@1.0.0-beta.4
echo "source 'https://rubygems.org'" > Gemfile
echo "gem 'compass', '0.12.2'" >> Gemfile
bundle install
# rbenv rehash # if you're using rbenv
npm install -g grunt-cli@0.1.6
npm install -g bower@0.8.6
```

```sh
mkdir <appname>
cd <appname>
yo webapp
```
