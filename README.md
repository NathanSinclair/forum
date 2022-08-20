Forum is an application that allows its users to register and log-in on a web portal.
Users can exchange posts and comments, and like/dislike posts and comments.
Each post is associated with up to four categories: sport, current affairs, travel, hobby.
Posts can be filtered by category and by liked posts.

Non registered users are able to view posts and comments. 
They are not permitted to add posts, comments, or likes/dislikes.

The programming languages and tools used for forum are:
Golang, HTML, CSS, Dockerfile, and Shell.

Forum authors:
Sonal, Kingsley, Nathan, Helena

To run project forum via Docker file:

-Download & turn on the docker application on your local device<br>
-Open VSC terminal within the forum folder<br>
-In the terminal, run "docker build -t forum ."<br>
-and then run "docker run -p 8080:8080 -it forum"<br>
-after above, you should be able to access the forum at http://localhost:8080<br>

Alternatively type "bash script.sh" in VSC terminal and press "y" when prompted.

To exit Docker type "exit" or <ctrl-D> in VSC terminal.

Forum application is deployed on: https://damp-sands-54043.herokuapp.com/


