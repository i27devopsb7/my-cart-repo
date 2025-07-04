// tool section at the pipeline level
pipeline{
    // agent block
    agent any

    // tools block at the pipeline level
    tools {
        maven 'maven-3.8.8'
    }

    // stages block 
    stages {
        stage("Maven") {
            steps {
                echo "Hello, welcome to maven section"
                sh "mvn --version"
                // mvn 3.8.8 > java 21
            }
        }
        stage ('differntmaven'){
            tools {
                jdk 'JDK-17'
            }
            steps {
                echo "Hello, coming from differnt java version"
                sh 'mvn --version'
                // mvn 3.8.8 > java 21
            }
        }
    }
}
