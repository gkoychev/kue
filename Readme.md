# Kue-Mod

  - removed full-text search for kue backend (for less trash in redis)
  - added unique job support (just add 'uid' as in example below)

```js
jobs.create('task', {
    uid: 'calc_some_for_user_2'
  , email: 'tj@learnboost.com'
  , somedata: 'some data'
}).save();
```


# Kue

  Kue is a priority job queue backed by [redis](http://redis.io), built for [node.js](http://nodejs.org).

## Installation

    $ npm install kue-mod

## Documentation
  
  for original documentation see
  [https://github.com/LearnBoost/kue](https://github.com/LearnBoost/kue)
