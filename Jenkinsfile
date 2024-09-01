pipeline {
    agent none

    stages {
        stage('Hello World Test') {
            agent {
                docker { 
                    image 'hello-world' 
                }
            }
            steps {
                sh 'echo "Running Hello World Docker Container"'
                sh 'docker run hello-world'
            }
        }
    }
}
