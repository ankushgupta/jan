pipeline {
    agent any
    
    parameters {
     string defaultValue: 'test', name: 'USERNAME'
        }
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo "$USERNAME"
            }
        }
    }
}
