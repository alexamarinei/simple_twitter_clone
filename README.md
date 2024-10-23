# simple_twitter_clone


Overview
Twimba is a simple Twitter-like app built with JavaScript. It allows users to create tweets, like and retweet posts, and reply to tweets. The app uses a mock dataset to simulate tweets, making it an interactive but basic version of Twitter.

Features
Post Tweets: Users can write and post new tweets.
Like and Retweet: Users can like and retweet existing tweets.
Reply to Tweets: Users can view and hide replies under tweets.
Dynamic Updates: The tweet feed updates automatically when users interact with tweets.
How It Works
The app listens for clicks on buttons for likes, retweets, replies, and new tweets. When a user interacts with a tweet, it updates the tweet data and refreshes the feed.

Main Functions
handleLikeClick(tweetId): Handles liking or unliking tweets.
handleRetweetClick(tweetId): Manages retweeting or un-retweeting.
handleReplyClick(replyId): Toggles the display of replies.
handleTweetBtnClick(): Adds a new tweet to the feed.
render(): Renders the updated tweet feed.
Running the App
Download the project files.
Open index.html in your browser.
Type a tweet and press "Tweet" to add it to the feed.
Click the like, retweet, or reply icons to interact with tweets.
Tweet Data
The app uses pre-defined mock tweets stored in data.js, which includes details like user handles, profile pictures, likes, retweets, and replies.

Technologies Used
JavaScript for logic.
HTML/CSS for structure and styling.
Font Awesome for icons.
UUID for generating unique tweet IDs.
Future Enhancements
Add saving of tweets with a backend.
User accounts and personalized feeds.
Ability to post replies directly.
