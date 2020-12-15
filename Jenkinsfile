pipeline {
  agent any
    stages {
      stage('directing to code directory') {
        steps {
          sh 'cd code'
          echo 'Entered to code Directory'
        }
      }
    
      stage('directing to web directory') {
        steps {
          sh 'cd web'
          sh 'npm install'
        }
      }
    
      stage('running the application') {
        steps {
          sh 'npm start'
        }
      }
  }
}
