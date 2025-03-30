# Getting the sid

Without a testclient key you may have to copy your data into the site every time you refresh the page. This can be skipped by using a config file.

## Requirements

- Google Chrome
- Pokemon Showdown account

In the config directory create a copy of the file testclient-key-example.js and rename it testclient-key-js.

This file requires a unique value in place of 'sid'. You can get an sid by going to <https://play.pokemonshowdown.com/> while logged into an account an opening devtools. In devtools navigate to the Application tab, open the Cookies dropdown menu and click on the cookie labelled 'https://play.pokemonshowdown.com/' to view its contents. One of the cookies listed will be 'sid', click on it and the Cookie Value should be dispalyed below.

First make sure that Show URL-decoded is checked, then copy the Cookie Value, paste it into your config file and save the file.