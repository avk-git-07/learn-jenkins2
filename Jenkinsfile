pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                echo "This is Build"
            }
        }
        stage ('Test') {
            steps {
                sh "echo This is Test"
            }
        }
        stage ('Deploy') {
            steps {
                sh "echo This is Deploy"
            }
        }
    }

    post {
        always {
            echo "This section runs always"
        }
        success {
            echo "This section runs when it is success"
        }
        failure {
            echo "This section runs when it is failure"
        }
    }

}

