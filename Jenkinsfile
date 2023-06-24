pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                if (params.branch==master) {
                echo 'Hello World'
                }     
                if (params.branch==dev) { 
                      echo "hello dev"
                }
                }
                
            }
        }
    }
}

