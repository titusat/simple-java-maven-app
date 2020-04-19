pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Hello World' >> /tmp/build
            }
        }
        stage('Test') {
            steps {
                echo 'Stage Test' >> /tmp/test
            }
        }
    }
}
