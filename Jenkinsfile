pipeline {
    agent any 
    stages {
        stage('Build Master') { 
            when{
              branch 'master'
            }
            steps {
                echo 'Building master'
            }
        } 
        stage('Build Dev') {
            when{
               brunch 'dev'
         }
            steps {
                echo 'Building dev'
         }
       }
    }
}
