# FirefoxOS-Dropbox

An example Firefox OS app that uses [dropbox-js](https://github.com/dropbox/dropbox-js) library.

## Usage

* Get a copy of `dropbox.js` using [dropbox-js](https://github.com/dropbox/dropbox-js), put it in `app` AND `endpoint`
* Host the `endpoint` somewhere and configure `receiverUrl` in `index.html` for that endpoint.
* Use the simulator or deploy the app to your phone to test

## Notes

Read more at [dropbox-js issue 81](https://github.com/dropbox/dropbox-js/issues/81)
See the source of the [Contacts](https://github.com/mozilla-b2g/gaia/blob/master/apps/communications/contacts/oauth2/js/parameters.js) app for
OAuth2 flows.
