Reddit CC
================

A simple reddit clone I made for my second assignment.

### About the stack

Rails: 
+ Version: 4.2.6

Gems:
+ Devise, ~> 3.5, >= 3.5.6
+ Bootstrap-sass, ~> 3.3, >= 3.3.6
+ Acts_as_votable, ~> 0.10.0
+ Simple_form, ~> 3.2, >= 3.2.1
+ Mmenu-rails, ~> 5.5, >= 5.5.3 // This version does not work, had to manually add in the files from the plugin

### Development

Overall basic functionality is out of the way, the Users can sign up, submit posts, subscribe to subreddits etc.

Currently Known bugs:

+ User comments on posts are no longer displaying user emails and only displaying their id
+ There appears to be an issue with upvotes and downvotes causing the open content menu to duplicate for all subsquent posts underneath that post.
+ Gifs image submits do not seem to function correctly in the open image menu.


Upcoming Features:

+ Admin Users
+ Custom homepage depending on what you're subscribe to
+ Automatic generation of thumbnails next to the posts
