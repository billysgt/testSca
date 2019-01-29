pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        git(url: 'https://github.com/billysgt/testSca.git', branch: 'branch2')
        sh "${tool name: 'sbt', type:'org.jvnet.hudson.plugins.SbtPluginBuilder$SbtInstallation'}sbt compile"
      }
    }
  }
}
