pipeline {

    agent any

    stages {
      stage(‘Build’) {
        steps {
          sh 'sudo docker-compose up --build'
          /*sh '''
            echo "DIt wordt uitgevoerd in mijn jenkins container"
            echo "Install"
            echo " Test"
            echo "deploy"
            '''
            */
        }
      }
    }
}
