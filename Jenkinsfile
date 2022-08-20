pipeline {
    agent any
    triggers { cron (' * * * * *') }
    stages {
        stage ('First Stage') {
            steps {
                sh 'ls -laht'
            }
        }
        stage ('Second Stage') {
            steps {
              sh 'whoami'
            }
        }
    }
}