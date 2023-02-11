def myfn() {
  println "function is been called"
}

pipeline {
  agent any 
  stages {
    stage('welcome to jenkins') {
      steps {
        script {
          myfn()
        }
      }
    }
  }
}
