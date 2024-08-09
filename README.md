# ClikBate-App



 

**Introduction: CLIKBATE**  

 

 

Hi there,  

 

 

Clikbate is social media platform focused on interactive content, were users can be creative with their ideas as well as leverage the power of ChatGPT AI to create amazing contents.  

 

Clikbate was developed using; ReactJS, React redux, Typescript, NodeJS and express Js, Nginx, AWS services (RDS, S3 bucket, Route 53, EC2, Cloud front, Elastic trancsode) for deploying data, media files and build files respectively on the cloud.  clikbate.com  

 

Note: Due to sensitive data (credentials,secrets, passwords, API keys) the code for this project is located in a private repository. 

 


**Clickbate Design and Architecture** 
<img width="876" alt="Screenshot 2024-04-28 at 20 45 39" src="https://github.com/workdontstop/clikbateSocial/blob/main/unnamed.jpg">





![unnamed](https://github.com/workdontstop/clikbateSocial/blob/main/Screenshot%202024-04-28%20at%2020.45.39%20(1).png)




**System Overview** 

 

AWS Route 53 : DNS requests to clikbate.com are handled by Amazon Route 53, a highly available and scalable Domain Name System (DNS) web service. 

 

AWS CloudFront : is a content delivery network (CDN) with edge locations around the world. It can cache static and streaming content and deliver dynamic content with low latency from locations close to the users. 

 

ChatGPT AP1: is integrated with clikbate.com, using ChatGPT image generator to produce creative images.  

 

S3 bucket: AWS S3 bucket stores all static content, images, and videos. The AWS CloudFront delivers non-cached content by fetching from the S3 bucket. 

 

AWS Elastic transcoder: is used to convert media files from their original source format into different formats that will play on smartphones, tablets and PC's. 

 

NGINX: acts as a load balancer routing user requests across all servers capable of fulfilling those requests. 

 

EC2 instance: acts as the web server were the clickbate application is deployed. 
