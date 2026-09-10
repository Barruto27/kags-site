# kags-site

The public home page and privacy policy for **Kags Assistant**, a private
single-user Telegram bot.

These two pages exist because Google requires an application home page and a
privacy policy URL on a registered domain before an OAuth app using a sensitive
scope can be published. Publishing is what removes the 7-day refresh-token
expiry that applies to apps left in "Testing".

Served by GitHub Pages at <https://kags.xyz>. The `CNAME` file binds the custom
domain; deleting it reverts the site to the github.io address and breaks the
OAuth configuration.

The bot itself lives in a separate private repository.
