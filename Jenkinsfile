pipeline {
  agent any 
  stages {
    stage('working with conditions') {
      steps {
        script {
          input message: 'enter var1 value', parameters: [string(name: 'VAR1', trim: true)]
          if ( VAR1 == 10) {
            println "my var1 value is 10"
          }
          else {
            println "my var1 value is not 10"
          }
        }
      }
    }
  }
}
