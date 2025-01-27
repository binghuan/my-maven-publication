# Project: my-maven-publication
An example to publish AAR to private maven repository

## Build hello.aar
```bash
cd step_1_build_and_publish_hello_aar;    
gomobile bind -target=android	
```

## publish hello.aar to private maven repository
```bash
cd step_1_build_and_publish_hello_aar;   
gradle publish  
```  

![](./images/cmd_gradle_publish.png)

## Finally, you can see a new package on repository
![](./images/sonatype_nexus_repository_manager.png)

## Sample to get tag as version 
![](./images/getversionname.png)


## Illustration: 
![](./images/Slide1.png)
![](./images/Slide2.png)
![](./images/Slide3.png)

![](./images/Slide4.png)
![](./images/call_hello_aar_on_android.png) 

## Reference: 
<https://docs.gitlab.com/ee/user/packages/maven_repository/>  
<https://juejin.im/post/6844903926551019527>