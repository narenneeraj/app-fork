pipeline {
agent any
  stages {
    stage ('Test'){
      steps {
      sh ''' 
      npm install
      sudo pm2 delete all
      sudo pm2 start ./bin/www
      echo "Hi Narendra"
      '''
      }
      }
  }
}
