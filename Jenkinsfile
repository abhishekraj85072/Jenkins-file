pipeline {
  agent any
  stages {
    stage('github pull') {
      steps {
        git(url: 'https://github.com/abhishekraj85072/SampleWebApp.git', branch: 'master', poll: true)
      }
    }

  }
}