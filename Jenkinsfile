pipeline {
agent any
  stages {
    stage ('Test'){
      steps {
      sh 'npm install'
      sh 'pm2 delete all'
      sh 'pm2 start ./bin/www'
      }
      }
  }


}
