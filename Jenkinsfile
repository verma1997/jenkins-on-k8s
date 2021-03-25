pipeline {
    agent {
        label "jenkins-slave"
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('First Stage') {
            steps {
                echo "This is running in slave agent."
            }
        }
    }
}