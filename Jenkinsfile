pipeline {
    agent any
    stages {
        stage ("code checkout") {
            steps {
            git "https://github.com/akramshaik12345/spring-petclinic-microservices.git"
            }
        }
        stage ("build") {
            steps {
                bat 'mvn compile'
            }
        }
        
    }
}
