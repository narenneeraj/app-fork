pipeline {
agent any
  stages {
    stage ('Test'){
      steps {
      sh ''' 
      npm install
      pm2 start ./bin/www
      echo "Hi naren"
      '''
      }
      }
  }
}
