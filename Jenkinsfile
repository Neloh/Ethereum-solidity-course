pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        sh 'echo \'Hello Ethereum Smart Contracts from Jenkins!\''
      }
    }

    stage('npm unit tests') {
      steps {
        sh 'cd /var/jenkins_home/workspace/Ethereum-solidity-course_dev && npm i && npm run test:unit'
      }
    }

  }
}