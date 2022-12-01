pipeline {
  agent any
  stages {
    stage('DEMO') {
      parallel {
        stage('DEMO') {
          steps {
            sh '''echo \'Hello\'
sleep 10'''
          }
        }

        stage('stage2') {
          steps {
            sh '''echo \'hello world\'
sleep 10'''
          }
        }

      }
    }

    stage('Compile') {
      steps {
        sh '''echo \'Compile\'
sleep 10'''
      }
    }

  }
  environment {
    WHO = 'SREEJA'
  }
}