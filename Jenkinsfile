pipeline {
    agent any
    
    environment {
        VAR1 = 'Hola'
        VAR2 = 'Mundo'
    }    
    
    stages {
        stage('Build') {
            steps {
                sh 'echo $VAR1'
                sh 'echo $VAR2'
            }
        }
    }
}
