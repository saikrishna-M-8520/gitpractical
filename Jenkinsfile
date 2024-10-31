pipeline {
    agent any

    stages {
        stage('Gitclone') {
            steps {
                echo 'Git code '
            }
        }
        stage('Maven Build') {
            steps {
                echo 'Maven build'
            }
        } 
        stage('Sonar code quality') {
            steps {
                echo 'Sonar code quality'
            }
        }
        stage('Nexus artifactory upload') {
            steps {
                echo 'Nexus artifact upload'
            }
        }        
        
    }
}
