// tool section at the pipeline level
pipeline{
    agent {
        label "java-slave"
    }
    stages {
        stage("Maven") {
            steps {
                echo "Hello, welcome to maven section"
                sh "mvn --version"
            }
        }
    }
}
