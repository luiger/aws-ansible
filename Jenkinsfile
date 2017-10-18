pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        isUnix()
        timestamps() {
          timeout(time: 1)
          catchError() {
            echo 'сс'
          }
          
        }
        
      }
    }
  }
}