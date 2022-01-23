pipeline {
    agent any
    
    parameters {
     string defaultValue: 'test', name: 'USERNAME'
     string defaultValue: 'test', name: 'PASSWORD'
        }
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo "$USERNAME"
                echo "$PASSWORD"
            }
        }
         stage('dev') {
            steps {
                echo 'dev environment'
                echo "$USERNAME"
                echo "$PASSWORD"
            }
         }
          stage('prod') {
            steps {
                echo 'prod environment'
                echo "$USERNAME"
                echo "$PASSWORD"
            }
          }
    }
}
