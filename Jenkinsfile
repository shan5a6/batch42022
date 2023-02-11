def myfn() {
  println "function is been called"
}
def myadd(int a,int b) {
  sum = a + b
  println "add of ${a} and ${b} is ${sum}"
}

pipeline {
  agent any 
  stages {
    stage('welcome to jenkins') {
      steps {
        script {
          myfn()
          myadd(100,200)
        }
      }
    }
  }
}
