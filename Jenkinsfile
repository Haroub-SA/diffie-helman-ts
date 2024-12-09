pipeline {
  agent any
  stages {
    stage('clone repo') {
      steps {
        echo 'cloning repository'
        git(url: 'https://github.com/Haroub-SA/AquaFish.git', branch: 'dev')
      }
    }

  }
}