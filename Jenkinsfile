pipeline {
    agent {
        docker {
            image 'maven:3.6-jdk11' 
            args '-v /var/lib/jenkins/.m2:/root/.m2' 
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}