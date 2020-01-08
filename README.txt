#Follow the instructions to run the multi machine app using Ansible

##1. Download all the files from this github repo
##2. Run GitBash as administrator and cd to the folder with the code
##3. Run "vagrant up" to spin the machine up
##4. You will get a message saying the app is running

###You can access the app on your browser using the "development.local" URL
###You can access the posts page using the "development.local/posts" URL

##To stop the app follow these commands

##1. ctrl+c
##2. vagrant ssh app
##3. kill -9 -1
##4. vagrant destroy -f