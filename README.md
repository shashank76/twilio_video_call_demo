# Twilio Video Quickstart for JavaScript

This application should give you a ready-made starting point for writing your
own video apps with Twilio Video. Before we begin, we need to collect
all the config values we need to run the application:

- Account SID: Your primary Twilio account identifier - find this [in the console here](https://www.twilio.com/console).
- API Key SID: Used to authenticate - [generate one here](https://www.twilio.com/console/runtime/api-keys).
- API Key Secret: Used to authenticate - [just like the above, you'll get one here](https://www.twilio.com/console/runtime/api-keys).

## A Note on API Keys

When you generate an API key pair at the URLs above, your API Key Secret will only
be shown once - make sure to save this in a secure location,
or possibly your `~/.bash_profile`.

## Setting Up The Application

Create a configuration file for your application:

```bash
cp .env.template .env
```

Edit `.env` with the configuration parameters we gathered from above.

Next, we need to install our dependencies from npm:

```bash
npm install
```

Now we should be all set! Run the application:

```bash
npm start
```

Your application should now be running at [http://localhost:3000](http://localhost:3000). Just enter
the name of the room you want to join and click on 'Join Room'. Then,
open another tab and join the same room. Now, you should see your own
video in both the tabs!
