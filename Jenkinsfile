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
                echo "****** Welcomd to groovy block******"
                script {
                        // i want to define a varible 
                    // def variablenam = "value"
                    def course = "rag"

                    // if condition
                    if (course == "k8s")
                        println("Thanks for enrolling")
                    else
                        println("Do enroll for k8s")
                    //println("Thanks for enrolling to ${course} course")
                }
            }
        }
    }
}

// ${course} , ${env.course}, ${params.course}

