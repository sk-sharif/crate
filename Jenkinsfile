pipeline {
  agent any
    stages {
      stage('directing to code directory') {
        steps {
          sh 'pwd'
          sh 'cd code'
          echo 'Entered to code Directory'
          sh 'pwd'
          sh 'cd web'
          echo 'Entered to web Directory'
          sh 'npm install'
          sh 'npm start'
        }
      }
  }
}
