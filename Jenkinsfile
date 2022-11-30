pipeline {
agent any
  stages {
    stage ('Test'){
      steps {
      sh ''' 
      ls -ltrh
      pwd
      npm install
      '''
      sh 'pm2 start ./bin/www'
      }
      }
  }


}
