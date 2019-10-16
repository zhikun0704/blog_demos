pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        svn(poll: true, url: 'svn://192.168.6.17/ITE-TOOL/04Source/trunk/ite-cutover-tool')
        sh 'mvn version'
      }
    }
  }
}