# Plaid / Banking MERN

Minimal full-stack MERN app with authentication using passport and JWTs.

## Configuration

Make sure to add your own `MONGOURI` from your [mLab](http://mlab.com) database in `config/keys.js`.

```javascript
module.exports = {
  mongoURI: 'YOUR_MONGO_URI_HERE',
  secretOrKey: 'secret'
};
```

## Quick Start

```javascript
// Install dependencies for server & client
npm install && npm run client-install
```
