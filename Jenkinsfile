pipeline {

    agent { label 'linux' }

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/samarasimha444/jenkins.git'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo cp index.html /usr/share/nginx/html/index.html
                '''
            }
        }

    }
}
