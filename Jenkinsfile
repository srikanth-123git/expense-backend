pipeline {

  agent {
    node {
      label 'ci-server'
    }
  }

  stages {

    stage('Lint Code') {
      steps {
        echo 'Lint Code'
      }
    }

    stage('Run Unit tests') {
      steps {
        echo 'Run Unit tests'
      }
    }

    stage('Run Integration tests') {
      steps {
        echo 'Run Integration tests'
      }
    }

    stage('Sonar Scan Code Review') {
      steps {
        echo 'Sonar Scan'
      }
    }

    stage('Release Software') {
      when { buildingTag() }
      steps {
        echo 'Release Software'
      }
    }

  }

}
