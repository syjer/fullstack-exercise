# fullstack-exercise

## Why

This exercise try to touch every part of the stack. The goal is to refresh and 
highlight the necessities when developing a "normal" application.

## What

The goal is to build an image gallery with some interesting features:

 - user image upload
 - tagging and search
 - exif metadata extraction
 - comments
 - login system
 - pagination
 
## Architecture
 
Like most modern web application, we will have a backend and frontend 
portion.

### Backend

#### Technical requirements

Expected the following technologies:

 - Persistence: use of Postgres (check the more advanced features)
 - REST api
 
### Frontend

#### Technical requirements

Expected the following "technologies":

 - use of a "javascript framework": angular (1.x or 6), react, vue
 - responsive design
 
 
## Requirements

In term of features, the application must have:

 - possibility to upload images (anonymous user)
 - display all the images with a thumbnail (with server side pagination)
 - when clicking on a thumbnail, it must show the full image
 - tag an image
 - search by tag
 - display exif information of an image
 - add a comment system
 - add a login system, make the "write operation" (upload image, delete an image,
   tagging an image, comments) require a login
