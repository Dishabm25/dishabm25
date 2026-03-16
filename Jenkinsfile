pipeline {
  agent any

  stages {
    stage('Clone') {
      steps {
        git url: 'https://github.com/Chinmayee-R12/jenkins-simple-demo.git',
          branch: 'main'
      }
    }
    stage('Run Script') {
      steps {
        sh 'python3 scrip.py'
      }
    }
  }
}
