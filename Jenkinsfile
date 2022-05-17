@Library('roboshop-shared-library@main') _

pipeline{
    agent any

    stages{
        stage('Lint Checks') {
            steps{
              script{
                sample.info('Starting', 'google.com')
            }
            sh '''
           # ~/node_modules/jslint/bin/jslint.js server.js
              echo Link checks
            '''
            }
        }
    }
}

