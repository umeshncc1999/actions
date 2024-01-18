##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-bharat-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-bharat-1.0
    
