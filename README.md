# docker-demo
Built a simple SpringBoot project in Docker .

## how to use

* first of all , you need download and Docker on your local system .

    My local operation system is MacOS 
    
    For how to use Docker on Mac , plz read My blog : [MacOS安装Docker](http://www.liumapp.com/articles/2017/12/27/1514347974172.html)
    
* built project by run command :  

        docker build -t docker-demo ../docker-demo 
         
* start project by run command : 

        docker run -d -p 8080:8080 docker-demo
        
  than you can see this in your docker pannel:
  
  ![1.pic_hd.jpg](http://om40sen9v.bkt.clouddn.com/5c5540bc771e4805b339fef1d724762c.jpg)
    
* open your browser and visite : 

        http://127.0.0.1:8080
        
## attention

* You can view Dockerfile's syntax in [here](https://docs.docker.com/reference/builder/). 

    And this is quite necessary .
     
 
 
 