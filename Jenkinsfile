pipeline {
    agent any
    
    VAR1 = 'Hola'
    VAR2 = 'Mundo'
    
    stages {
        stage('Build') {
            steps {
                sh 'printenv'
                sh 'echo VAR1'
                sh 'echo VAR2'
            }
        }
    }
}
