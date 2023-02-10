pipeline {
  agent any 
  stages {
    stage('working with conditions') {
      steps {
        script {
          var1 = input message: 'enter var1 value', parameters: [string(name: 'VAR1', trim: true)]
          if ( var1 == 10) {
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
