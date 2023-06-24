pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                if (${branch==master})
                echo 'Hello World'
                      fi
                if (${branch==dev})  
                      echo "hello dev"
                      fi
            }
        }
    }
}

