pipeline {
    agent any
    stages {      
        stage('hello') {
            when {
                branch 'main'
            }
            steps {
               echo 'Hello World'
            }
        }
    }
}
