# Digit_Recognition_with_webpage
A simple web application in which the user can draw a digit and the application predicts the number


# Steps to use web app
1) Start any Static Content Server.eg Apache server
2) Run mnist.html on the server
3) Draw the digit on the black square
4) Click predict to get results
5) Click clear to clear the black sqaure


# Description of files contained in the repository
mnist.html    -   The web page 
model.json    -   Our model architechture converted into a js consumable by tensorflowjs converter. Also contains path to model weights (group 1-4)
group1-shard1of1,group2-shard1of1,group3-shard1of1,group4-shard1of1   -   Our model weights 
