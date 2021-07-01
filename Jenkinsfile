pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        sh '''sh \'\'\'chmod +x ./testscript.sh
                ./testscript.sh\'\'\''''
      }
    }

  }
  environment {
    NUMBERONE = '6'
    NUMBERTWO = '7'
  }
}