pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                if (params.branch == 'origin/master') {
                echo 'Hello World:${params.branch}'
                } else {    
              
                      echo "hello dev:${params.branch}"
                }
                }
                
            }
        }
    }
}

