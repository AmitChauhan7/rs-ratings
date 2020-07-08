pipeline {
  agent any



  stages {


    stage('Lint Checking') {
      steps {
        sh '''
          phplint html
          
        '''
      }
    }

  }

}