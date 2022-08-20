pipeline {
    agent any
    triggers { cron ('H/15 * * * *') }
    stages {
        stage ('First Stage') {
            steps {
                sh 'ls -laht'
                sh 'cat Jenkinsfile'
            }
        }
        stage ('Second Stage') {
            steps {
              sh 'whoami'
            }
        }
    }
}
