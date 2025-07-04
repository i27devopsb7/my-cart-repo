// timeout code 
pipeline {
    agent {
        label 'java-slave'
    }
    stages {
        stage ('Build'){
            steps {
                // i will wait for only 5 seconds.
                timeout (time: 5, unit: 'SECONDS'){
                    // my code will take 60 seconds to exucute
                    echo "*********** Sleeping for 60 seconds************"
                    sleep 60          
                }
            }
        }
    }
}
