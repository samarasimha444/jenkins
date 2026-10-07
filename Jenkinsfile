pipeline {

    agent {
        label 'linux'
    }

    stages {

        stage('Checkout') {
            steps {
                echo 'Code fetched from GitHub'
            }
        }

        stage('Display HTML Content') {
            steps {
                sh 'cat index.html'
            }
        }

    }

    post {
        success {
            echo 'Build Successful'
        }
    }
}
