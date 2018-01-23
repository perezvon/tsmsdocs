---
title: "Usage"
lesson: 2
chapter: 1
cover: "https://unsplash.it/400/300/?random?BoldMage"
date: "01/23/2018"
category: "tech"
type: "lesson"
tags:
    - programming
    - stuff
    - other
---

### Usage

```html
https://perezvon-tsms.herokuapp.com/MMMM DD YYYY
https://perezvon-tsms.herokuapp.com/MM-DD-YYYY
```
or

```html
https://perezvon-tsms.herokuapp.com/UNIXtimestamp
```

returns JSON in the format

```javascript
{"unix":"unixTimeStamp","dateStr":"MMMM DD, YYYY"}
```

Note that you cannot use dates formatted like MM/DD/YYYY or anything with slashes, really.
