pipeline {
  agent any 
  parameters {
    choice choices: ['dev', 'prod'], description: 'Select environment', name: 'ENV'
  }
  environment {
    JAVA_HOME = "/opt/java/bin"
  }

  
  stages {
    stage('working with variables') {
      steps {
        script {
          val1 = 20
          println "my val1 value is ${val1}"
          // parameters values 
          println "my parameter value is ${params.ENV}"
          // environment values
          println "my environment value is ${env.JAVA_HOME}"
        }
      }
    }
  }
}
