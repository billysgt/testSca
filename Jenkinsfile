pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        git(url: 'https://github.com/billysgt/testSca.git', branch: 'branch2')
        sh "./sbt clean compile"
      }
    }
  }
}
