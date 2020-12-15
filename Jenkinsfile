pipeline {
  agent any
    stages {
      stage('directing to code directory') {
        steps {
          sh '''
          pwd
          cd code
          echo 'Entered to code Directory'
          pwd
          cd web
          echo 'Entered to web Directory'
          npm install
          npm start
          '''
        }
      }
  }
}
