pipeline {
    agent any
       stage('Build') { 
        mvn compile
    }
    stage('Test') { 
       echo "test is running" 
    }
    stage('Deploy') { 
        mvn package
    }
}