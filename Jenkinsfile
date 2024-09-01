pipeline {
    agent none

    stages {
        stage('Hello World Test') {
            agent {
                docker { 
                    image 'busybox' 
                }
            }
            steps {
                sh 'echo "Running Hello World in Busybox Docker Container"'
                sh 'echo "Hello, World!"'
            }
        }
    }
}
