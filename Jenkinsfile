pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Running build automation'
               // sh './gradlew build --no-daemon'
                //archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
         stage('Testing') { 
            steps {
                echo 'Testing build automation'
               // sh './gradlew build --no-daemon'
                //archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
         stage('Deploy') { 
            steps {
                echo 'Deploying build automation'
               // sh './gradlew build --no-daemon'
                //archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
