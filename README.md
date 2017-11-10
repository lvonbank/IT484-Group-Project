# IT484-Group-Project


## Getting Up And Runnning

1.) Clone the repo locally

2.) `cd` into the root directory

3.) Run `bundle install --without production`

4.) Run `bundle exec rake db:setup`

You should now be setup for local development. 

# For Local Environemnts

You can verify by running `rails server` and navigating to the URL and verifying the project is displayed correctly.

# For Cloud9 Environments
You can verify by running `rails server -p $PORT -b $IP` to start the app. Cloud9 will pop up a window showing the URL to visit in your browser to interact with the running app.