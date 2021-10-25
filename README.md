# k8-node-microservice-skaffold
Test of blog microservice application using kubernetes, docker, node.

slight oversight... need to open /etc/hosts and set posts.com to redirect to localhost to be able to run this project

from ~ open ```/etc/hosts``` and add the following line: ```127.0.0.1 posts.com```

then, to run all microservices run ```skaffold dev``` and go to posts.com in your browser.
