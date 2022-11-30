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
      sudo pm2 start ./bin/www
      sudo pm2 list
      '''
      }
      }
  }


}
