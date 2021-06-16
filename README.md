# SyncPlay
[Access the application here!](https://syncandplay.herokuapp.com/)

SyncPlay is a real-time online video synchronization platform. You can enjoy any video available online with friends who may not be next to you!

SyncPlay currently supports YouTube and essentially any .mp4/.webm on the internet with the HTML5 Player!

[![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](http://forthebadge.com)

[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)


---

### Dependencies

Socket.io

Node.js

Express

YouTube Data API V3

---

### How to run locally

##### How to run the server

Install Dependencies
```
npm install
```

Create a `.env` file and add API keys for YouTube Data API V3 as YT3_API_KEY

Run the server
```
node server
```

Access the page by going to localhost:3000

##### How to run CI tests

```
npm test
```

---

