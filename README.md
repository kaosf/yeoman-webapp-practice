# Yeoman webapp Practice

For getting started, refer [this repository](https://github.com/kaosf/yeoman-practice).

```sh
# run at only the first time
npm install -g yo@1.0.0-rc.1.1
echo "source 'https://rubygems.org'" > Gemfile
echo "gem 'compass', '0.12.2'" >> Gemfile
bundle install
# rbenv rehash # if you're using rbenv
npm install -g grunt-cli@0.1.9
npm install -g bower@0.10.0
```

```sh
mkdir <appname>
cd <appname>
npm install generator-webapp@0.2.6
yo webapp
```

## References

* [Yeoman - Modern workflows for modern webapps](http://yeoman.io/)
