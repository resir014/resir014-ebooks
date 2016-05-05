# resir014-ebooks

[twitter_ebooks](https://github.com/mispy/twitter_ebooks)-based ebooks bot for [@resir014](https://twitter.com/resir014).

## Usage

```bash
git clone https://github.com/mispy/ebooks_example.git
cd ebooks_example
bundle install
ebooks archive resir014 corpus/resir014.json
ebooks consume corpus/resir014.json
```

Populate bots.rb with your auth details, the bot username and model name, then:

`ebooks start`

Also runs as a Heroku app! See the [twitter_ebooks](https://github.com/mispy/twitter_ebooks) README for more information.
