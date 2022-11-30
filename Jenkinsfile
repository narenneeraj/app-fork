pipeline {
agent any
  stages {
    stage ('Test'){
      steps {
      sh ''' 
      ls -ltrh
      pwd
      whoami
      npm install
      pm2 start ./bin/www
      '''
      }
      }
  }


}
