pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                if (${branch==master})
                echo 'Hello World'
                      
                if (${branch==dev})  
                      echo "hello dev"
                }
                
            }
        }
    }
}

