# Website Source

This is the source code for the class website. This website is done using
middleman, which is a ruby static website generator. It uses middleman-deploy
for deployment to the github pages site. 

To work on this site, install ruby and bundler, then run

    $ bundle install

in the root directory. That should install all the gems you need. Then,
run a middleman server with

    $ middleman 

and connect to

    http://localhost:4567

When you're done, commit your changes and do

    $ middleman deploy

which will build and upload the site.
