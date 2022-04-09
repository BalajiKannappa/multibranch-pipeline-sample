pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
       echo 'Hello'
      }

    }
    stage(){

     when{
      branch "fix-*"
     }
     steps{
       sh '''
        cat README.md
	'''

     }

    }
  }
}
