# Project: my-maven-publication
An example to publish AAR to private maven repository

## Build hello.aar
<code>
cd step_1_build_and_publish_hello_aar   
gomobile bind -target=android	
</code>

## publish hello.aar to private maven repository
<code>
cd step_1_build_and_publish_hello_aar   
gradle publish  
</code>  

![](./images/cmd_gradle_publish.png)

## Finally, you can see a new package on repository
![](./images/sonatype_nexus_repository_manager.png)

## Illustration: 
![](./images/Slide1.png)
![](./images/Slide2.png)
![](./images/Slide3.png)
![](./images/Slide4.png)
![](./images/call_hello_aar_on_android.png)