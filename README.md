# Camp-Cipher

## Contributor(s):
   + Victor Ginelli

## Summary:
> Camp Cipher is a social music website where artists are encouraged 
>to build off one another's work in order to create an environment 
>where good flow and potent lyricis stand out. Users are allowed to 
>"start a campfire" by contributing their best single or four-bar 
>rhyme scheme. A "campfire circle" is then opened up to the public to
>allow other artists to join in and post their own additions to the 
>freestyle session, where it was left off. These additions can be 
>voted on by other users in the campfire, and the highest voted will 
>be featured under the original posters lyrics. The original poster 
>can also choose his/her original post or an addition to be the hook 
>and will subsequently be featured at the top of the page. All 
>contributions to the site are saved in a user profile for you and 
>are open for later review.

## Users: 
   + Music Artists
   + Lyricists
   + anyone that likes to rhyme!

## MVP: 
   + A "home feed" that shows all posts by users in chronological order
   + Users are able to create an individual account
   + Users are able to make posts under the name of their account
   + Users posts are tied to the users account for later review

   + Outreach Goals:
      + Every post will have a feed of its own that shows subscribers, likes, comments, and ranking
      + A post is limited to 240 characters and can be labeled as a one-bar, 4-bar, or hook

## Functionality:
>Camp Cipher allows the user to create an account with an individual email and password. The user can use that account to make posts onto the main feed. Posts are attached to user accounts so its easy to go back to review past posts. Type in 0.0.0:3000/users/"your_id".

##Installation Steps
   1. Download the git repository and open up the main folder/Camp-Cipher
   2. Make sure you have the proper gems install by running 'bundle' in the terminal
   3. Start a rails server by running 'rails s' in the terminal
   4. Open http://0.0.0.0:3000/ in a web browser of your choice

## Major Issues/Known Bugs
   + cannot view a complete list of users
   + no distinction between user types (e.g. admin, develope, etc)
   + CSS is hard so I followed a tutorial and used bootstrap to make things look nice

## References:
   + theodinproject.com
   + railstutorial.org

## Gems:
   + 'will_paginate'
   + 'bootstrap-will_paginate'
   + 'faker'
   + 'bcrypt'
   + 'bootstrap-sass',