# Jazzcat Client

This repo contains the client library for Mobify's Javascript Concatenation
service, Jazzcat. The client API is MIT licensed, but use of it with the
backend service requires you to be a Mobify Cloud user (https://cloud.mobify.com)

## Installation

First, you will need to install grunt-cli and bower globally:

    npm install -g grunt-cli bower

Then install the local dependencies:

    npm install
    bower install

## Testing

    grunt test

And if you have Saucelabs credentials:

    grunt saucelabs
