pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo "***** Coming from Build stage ********"
            }
        }
        stage ('groovystage') {
            steps {
                script {
                        // i want to define a varible 
                    // def variablenam = "value"
                    def course = "k8s"
                    println("Thanks for enrolling to ${course} course")
                }
            }
        }
    }
}

// ${course} , ${env.course}, ${params.course}
