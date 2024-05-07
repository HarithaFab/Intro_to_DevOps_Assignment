pipeline {
    agent any
    tools {
        jdk 'java17'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                echo 'Build in progress ...'
                dir('MayFolder') {
                    bat 'cd'
                }
            }
        }
     }
}

 
     
 
                 
	
