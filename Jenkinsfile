pipeline {
  agent any



  stages {


    stage('Lint Checking') {
      steps {
        sh '''
          composer require overtrue/phplint --dev -vvv
          ./vendor/bin/phplint html
          
        '''
      }
    }

  }

}