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
        sh 'cd /home/sibonelo/Documents/blockchain_tutorial/Ethereum-solidity-course && npm i && npm run test:unit'
      }
    }

  }
}