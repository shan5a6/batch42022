pipeline {
  agent any 
  stages {
    stage('working with loops') {
      steps {
        script {
          a=1
          while( a <= 10) {
            println "a value is ${a}"
            a = a + 1
          }
          for(i=1;i<=10;i++) {
            println "my i value is ${i}"
          }
          lis1=[10,20,30,40]
          for (ele in lis1) {
            println "my ele is ${ele}"
          }
        }
      }
    }
  }
}
