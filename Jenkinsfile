pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                if (params.branch == 'master') {
                echo 'Hello World'
                } else {    
              
                      echo "hello dev"
                }
                }
                
            }
        }
    }
}

