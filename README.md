# Reddit API by theroyakash

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Sophisticated Reddit API for free. Unlimited calls for memes, cute cat pictures, and anything you can find on reddit.

# Make your apps with Reddit API
### URL
`GET https://getredditapi.theroyakash.repl.co/api/v1?r={subreddit}&limit={count}`.
### Arguments
- `subreddit` name. For example: dankmemes, aww, pics etc.
- `limit` - Total number of result that you want to get. (Maximum of 100 per search)

### Examples
For example to get 4 hot posts in subreddit `dankmemes`use the following link for `GET` request

`GET http://getredditapi.theroyakash.repl.co/api/v1/?r=dankmemes&limit=4`

### Returns
```json
{
   "post_0":{
      "author":"dicemaze",
      "post_url":"https://i.imgur.com/XNFiUHo.png",
      "upvotes":366,
      "upvote_ratio":"92.0% people upvoted"
   },
   "post_1":{
      "author":"IdontEvenKFCbruh",
      "post_url":"https://i.redd.it/8xyjxp07yxh51.jpg",
      "upvotes":51772,
      "upvote_ratio":"95.0% people upvoted"
   },
   "post_2":{
      "author":"udipadhikari",
      "post_url":"https://i.redd.it/x8xzz1ku6xh51.png",
      "upvotes":36263,
      "upvote_ratio":"96.0% people upvoted"
   },
   "post_3":{
      "author":"DuccBoii",
      "post_url":"https://i.redd.it/wocqkydl0yh51.png",
      "upvotes":5608,
      "upvote_ratio":"94.0% people upvoted"
   }
}
```
### Example in r/aww

Now let's get first 5 posts from r/aww which are in hot.
`GET http://getredditapi.theroyakash.repl.co/api/v1/?r=aww&limit=5`

### Returns
```JSON
{
   "post_0":{
      "author":"N8theGr8",
      "post_url":"https://discord.gg/UXfd5Pn",
      "upvotes":685,
      "upvote_ratio":"97.0% people upvoted"
   },
   "post_1":{
      "author":"N8theGr8",
      "post_url":"Null",
      "upvotes":30,
      "upvote_ratio":"86.0% people upvoted"
   },
   "post_2":{
      "author":"Beerus1995",
      "post_url":"https://i.imgur.com/lZcuOkS.jpg",
      "upvotes":45244,
      "upvote_ratio":"95.0% people upvoted"
   },
   "post_3":{
      "author":"sanjiv_gawali",
      "post_url":"https://v.redd.it/4gnvu7enqxh51",
      "upvotes":15065,
      "upvote_ratio":"98.0% people upvoted"
   },
   "post_4":{
      "author":"f__h",
      "post_url":"https://v.redd.it/njvsy7r8yxh51",
      "upvotes":8675,
      "upvote_ratio":"97.0% people upvoted"
   }
}
```

### TO-DO
- API Now serves only hot Posts. In future I'll try to add top and new sort methods to the API.
## Contributing [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://www.iamroyakash.com/contact)
You are very welcome to contribute. Check the To-do to get the idea what this project needs. Start contributing by making a issue [here]().

License
----
GNU General Public License v3.0

**Free API, Hell Yeah!**
