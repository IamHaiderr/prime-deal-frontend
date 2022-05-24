###for local testing 

after downloading from githug
    -first use npm instal to install all required dependencies

    - npm start after npm install to run 

    if  you are testing backend and frontEnd in differnt devices then 
    - change axios create baseUrl to the ip address of the computer instead of localhost only and dont change port

    - then npm run again 


for deployment to server
    - run npm install first to install all dependencies just to make sure

    - then run npm build to create a build ready bundle 
      which will be located in same folder with name build 
      compress everything in build and upload it to server and extract