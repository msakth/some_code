pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        sh '''sh \'\'\'chmod +x ./testScript.sh
./testScript.sh\'\'\''''
      }
    }

  }
  environment {
    NUMBERONE = '6'
    NUMBERTWO = '7'
  }
}