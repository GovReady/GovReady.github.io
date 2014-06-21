govready.github.io
==================

GovReady web site

## Using the Vagrant box

To work on GovReady.org content, you can:

```
# Clone the repo
git clone git@github.com:GovReady/GovReady.github.io.git
cd GovReady.github.io

# Launch the vagrant box with Jekyll
vagrant up
vagrant ssh
cd /vagrant     # /vagrant dir on guest is shared with GovReady.github.io dir on host

# Fix a bug in character encodings
export LC_ALL=en_US.UTF-8
export LANG=en_US.UTF-8

# Start jekyll server
jekyll serve -twP 4000 --watch
# wait while site generated

```

View content in your browser at http://localhost:4000/

Whenever you change a file, you will need to 'touch' the file on the Vagrant box for the Jekyll to know the file has been updated and needs to be regenerated.  

