# Deploying

In order to deploy (assuming we have your public SSH key and you have sufficient privileges to do so) you need to first add a new remote to your local repository...

    $ git remote add gdi git@gdicincinnati.com:gdicincinnati-com.git

Now you can deploy to production using the following command...

    $ git push gdi master
