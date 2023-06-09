##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root user

    docker build -t java-app .
    
##### push image to repositories

    docker tag java-app demo-app:java-1.0
    
