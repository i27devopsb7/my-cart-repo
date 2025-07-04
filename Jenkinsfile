pipeline {
    agent {
        label 'java-slave'
    }
    stages {
        stage ('Build'){
            steps {
                echo "Build stage from Main Branch"
            }
        }
        stage ('Scans'){
            steps {
                echo "Scans stage from Main Branch"
            }
        }
        stage ('dockerbuild'){
            steps {
                echo "docker stage from Main Branch"
            }
        }
        stage ('deployment'){
            steps {
                echo "deploying from Main Branch"
            }
        }
    }
}
