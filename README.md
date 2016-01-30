# openblog

Opening the doors to true open-source blogging by utilizing Github Pages hosting and Github Issues as storage media for posts and comments.

This is just an early prototype and would probably benefit from request caching and pagination.

### Setup

1. Fork.

2. To increase rate limit, create a Github Application and then [follow this simple guide](https://developer.github.com/changes/2012-12-06-create-authorization-for-app/) to generate an OAuth token without needing to use the webflow.

3. Change the globals in `lib/globals.js` to suit your needs:

```javascript
(function () {
  'use strict';

  window.USERNAME = 'your username here';
  window.REPO = 'your repo name here';
  window.TOKEN = 'your app access token here';
}());
```
