pipeline {
  agent any  
   stages {
    stage('Build') {
      steps {
        echo 'Hello'
      }

    }
    stage('cat README.md'){

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
