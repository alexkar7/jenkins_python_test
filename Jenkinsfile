pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "$(uname -a)"'
            }
        }
    }
    post {
        always {
            sh 'echo "I run always :D"'
        }
        success {
            mail to: 'alejandro.carmonamejia@gmail.com',
            subject: "Success Pipiline: ${currentBuild.fullDisplayName}",
            body: "Success Pipiline: ${currentBuild.fullDisplayName}"
        }
    }
}
