def myfn() {
  println "function is been called"
}
def myadd(int a=10,int b=20) {
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
          myadd()
          myadd(b=3000,a=2000)
        }
      }
    }
  }
}
