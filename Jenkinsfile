pipeline {

    agent any
    
    stages {
      stage ('echo build cause') {
        steps {
          sh '''
          currentBuild.getBuildCauses()
          '''
        }
      }
    }
}
