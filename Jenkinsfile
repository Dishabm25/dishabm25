pipeline {
  agent any

  stages {
    stage('Clone') {
      steps {
        git url: 'https://github.com/Chinmayee-R12/jenkins-simple-demo.git',
          branch: 'main'
      }
    }
    stage('Run Python Code') {
      steps {
         sh 'python3 -c "print(\'Hello from Jenkins!\')"'
      
         sh '''
           python3 -c "
print('Line 1')
print('Line 2')
print('This is Python code running without a file')
           "
         '''
      }
    }
  }
}
