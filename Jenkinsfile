pipeline {

    agent any
    
    stages {
      stage ('echo build cause') {
        steps {
          sh '''
          echo currentBuild.getBuildCauses()
          '''
        }
      }
    }
}
