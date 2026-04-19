pipeline{
  agent any
  stages{
    stage ('deploy to Apache') {
      steps{
        sh ''' sudo rm -rf /var/www/html/*
        sudo cp -r * /var/www?html/ '''
      }
    }
  }
}
