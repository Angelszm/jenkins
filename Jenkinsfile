pipeline {
    agent any
    triggers { cron ('H/15 * * * *') }
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
