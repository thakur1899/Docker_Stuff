# Docker_Stuff
Summer Internship 2020 -- Docker



To create a Docker image via GitHub follow the following steps:

Step 1: Create two file 
              A. Code file(Any language)
              B. Docker file
            
Step 2: Go to your terminal(Expecting Docker is already installed in your system) and then run this command

                sudo docker build -t mypyimage1:v2 https://github.com/thakur1899/Docker_Stuff.git
                
                sudo ----> "root",
                docker build ------>"to create a docker image",
                mypyimage1:v2------->"Imagename:version"  if version is not mentioned it will take latest (by default)
                https://github.com/thakur1899/Docker_Stuff.git ------>Your gitHub repo url.
                
Step 3: To run my code
          sudo docker run -it mypyimage1:v1 
          
          run command automatically create a conatainer . 


