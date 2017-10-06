pipeline {
  agent any
  stages {
    stage('Get Host Name') {
      steps {
        parallel(
          "Get Host Name": {
            sh 'echo "Getting Host Name"'
            
          },
          "Get Host Name 2": {
            sh 'echo "Get host name"'
            
          }
        )
      }
    }
    stage('Create Image') {
      steps {
        sh 'echo "Creating Image"'
      }
    }
  }
}