node('ci-server') {
  stage('Lint Code') {
    print 'OK'
  }
  stage('Run Unit tests') {
    print 'OK'
  }
  stage('Run Integration tests') {
    print 'OK'
  }
  stage('Sonar Scan Code Review') {
    print 'OK'
  }

  if(binding.hasVariable('TAG_NAME')){
    stage('Build Code') {
      print 'OK'
    }
    stage('Release Software') {
      print 'OK'
    }
  }
}

