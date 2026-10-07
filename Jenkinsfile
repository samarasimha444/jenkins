pipeline {

    agent { label 'linux' }

    stages {

        stage('Deploy HTML') {
            steps {
                sh '''
                sudo cp index.html /usr/share/nginx/html/index.html
                '''
            }
        }

    }
}
