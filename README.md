This a web app for organizing songs youre working on, I had a social media aspect to it with likes and comments 
but decided to remove it. I wanted to stick to the core of why I made it in the first place, so I could organize my own music. 

These are just notes for me:

x added a "details" portion of the "Post" model
x added a details portion to the createPost controller
x added details form in profile.ejs
x added <%= post.details %> ejs to my post.ejs
x it worked!

also song upload form

x added lyrics / tempo to post model
x added lyrics / tempo to createPost controller
x added lyrics / tempo forms to profile.ejs
x added <% post.lyrics %> and <% post.tempo %> to post.ejs
x it worked!

song uploader:
x added a song portion to Post model
x added a songId portion to the Post model
x added song and songId to createPost controller
x added a variable called music to createPost controller
x added song form to profile.ejs


removed multor file types: 
ext !== ".jpg" && ext !== ".jpeg" && ext !== ".png"

removed feed from profile and posts 

removed comment feature and like button feature, removed like comment and delete comment


added flowbite to header and footer

Need to add Google auth , soundcloud auth and an update form for editing

