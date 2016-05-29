Deltadrome.us
-----

This is simply some config options for the deltadrome.us site

This should be bundled up in a container at some point

## setup

For example, to serve the truthiness site at deltadrome.us/truth you'd need to
run the server on the port specified in `delta` nginx config as well as link
the static files to a `/www/data/` directory

`ln -s $HOME/workspace/scrape_the_truth/site /www/data/truth`

