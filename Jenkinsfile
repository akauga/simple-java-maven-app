pipeline {
  agent any
  stages {
    stage('Develpment') {
      steps {
        build(job: 'Build maven', propagate: true)
        task(name: 'TA Approval') {
          echo 'test'
        }
        
      }
    }
  }
  environment {
    Stage = 'Development'
  }
}