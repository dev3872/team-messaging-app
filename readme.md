# Team Messaging App
 ### The purpose of this app is to allow communication b/w people within an organisation.
 ## ENTITIES/MODELS
 1. **USERS** -   Every user has to sign up using his email id,  region, username and password.  Every user has to login using the correct username and password to use the application.
 2. **CHANNELS** - A channel is a container for a kind of communication. For eg : To discuss machine learning, a channel “eg: mltech” can be created.  Any logged in user can create a channel . A channel must contain the channel name, description, tags(can be multiple),  the users who are invited to the  channel. 
 3. **POSTS** - Any  user can create a post in a channel. A post should contain the message and the user who created that post. A series of posts in a channel will look at a discussion.
>A sample dataset of your choice regions and tags can be preloaded into respective collections.

>**Note** : Every entity should have a created and updated timestamps.
## BRIEF Functionality 
### The Main Page
  1. The user on logging in should see the channels he/she is a part of .The channel that the user participates in the most should appear at the top. On selecting a particular channel , he should be able to view the posts put on that channel and also create a post in that channel.The  messages should appear in a lazy loaded fashion rather than all the messages at once . The user should also be able to search a post on the basis of its content
  2. The user should also see a button to create a new channel . Using this button , he/she can create a new channel and invite other users to join this.
  3. The user interface of the app should be minimalistic and implemented in such a way that the clicks are minimised.

  ### Dashboard Page 
  
  In the dashboard page , we show a little bit of metrics derived from the above data. Below are the metrics to be shown.

   

   1. **Top 5 trending channels** - These should be the top 5 channels that have the most number of posts along with the number of posts per channel
   2. **Top 5 trending tags** - These should be the top 5 tags which are tagged on the most number of channels.
   3. **Top 5 trending regions** - These are the top 5 regions which have the most number of active users.
   4. **Top 5 users** - These are the top 5 users which have the most number of posts.
   > **Note** : There should be an option to view the above metrics in a date range.