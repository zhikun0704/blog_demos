pipeline {
  agent {
    node {
      label 'blog_demos'
    }

  }
  stages {
    stage('') {
      steps {
        svn(poll: true, url: 'svn://192.168.6.17/ITE-TOOL/04Source/trunk/ite-cutover-tool')
        sh 'mvn version'
      }
    }
  }
}