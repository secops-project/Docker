# Sigma.js Docker
If you have an application that uses the Sigma.js library, you can now run it without having to install all the prerequisites with something like this:

docker run -d -p 8000:8000 --name my_sigma.js --volume ~/MyAppDir:/app sigma.js

where MyAppDir is the folder that contains your application code.
