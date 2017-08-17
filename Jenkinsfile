pipeline {
  agent any
  stages {
    stage('asdasd') {
      steps {
        echo 'Shell'
        git(url: 'https://github.com/lordoftheflies/kryten-reports.git', branch: 'master', changelog: true, credentialsId: '1', poll: true)
      }
    }
  }
}