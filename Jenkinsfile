pipeline {
    agent any

    stages {
        stage('Run as ubuntu') {
            steps {
                script {
                    sh 'sudo -u ubuntu bash /home/ubuntu/main.sh'
                }
            }
        }
    }
}

