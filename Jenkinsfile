pipeline {
  agent any 
  parameters {
    choice choices: ['dev', 'prod'], description: 'Select environment', name: 'ENV'
  }
  environment {
    JAVA_HOME = "/usr/lib/jvm/java-11-openjdk-11.0.16.0.8-1.amzn2.0.1.x86_64/bin"
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
          sh "java -version"
        }
      }
    }
  }
}
