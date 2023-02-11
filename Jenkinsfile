pipeline {
  agent any 
  stages {
    stage('working with file operations') {
      steps {
        script {
          File file = new File("/tmp/mydata.txt")
          // println file.readLines()
          // for (line in file.readLines()) {
          //   println line
          // }
          file.write("Hi Team I am writing data from jenkins")          
        }
      }
    }
  }
}
