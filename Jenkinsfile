pipeline{
    agent any 
    stages {
        stage('Build') {
            steps {
                retry(3){
                    echo "Welcome to jenkins pipeline"
                    error "This will give some error"
                }
            echo "***** Printing after multiple retries *******"
            }
        }
    }
}
