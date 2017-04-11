You can create a public github repo for this project, use whatever
libraries you wish. Please include instructions on how-to build
your project in the README.md file in the root of your repository
as well as a section called Further Considerations in which you
describe issues you had while working on this challenge, as well
ideas to make this better in the future.


Instructions:

Project does not import any libraries, simply asks permissions
stated in the manifest and required by user on start-up.  Should
be able to cleanly download and run as is.


Issues:

#1. Learning how to programatically utilize the device
Camera.  Android developer docs clearly explained how to do so, as
well as StackOverflow examples from other users.

#2. Storing photos was simple as I had already played around with
Image paths for server and hosting purposes.  I utilized another
online example to store images on the device/external storage.
Target Uri was created and an image outputstream wrote the data to
that location.

#3. For the photo sequence aspect, I had used Handlers previously
with success and used them here. Unfortunately, I ran into an bug
with the Camera setPreview function not running correctly, with the only
solution being that it needed a larger window of time to reset
between shots. There is most likely a way to acheive the intended
half second wait between shots once I figured out what was causing the error.
