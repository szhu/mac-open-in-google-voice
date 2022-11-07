# Mac "Open in Google Voice"

This is a tiny app that can open `tel:` and `sms:` links in Google Voice in your
default browser.

Google Chrome can already do this, but my default browser is now Safari, and I
want to still be able to do this.

## How to use

Download or clone this repo. Then, to set this app as the default, run:

```sh
brew install duti
duti -s com.interestinglythere.GoogleVoiceLauncher tel
duti -s com.interestinglythere.GoogleVoiceLauncher sms
```

That's it!
