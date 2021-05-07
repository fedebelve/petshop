pipeline{
    agent any
    stages{

        stage('build'){
            steps{
                sh 'git pull origin master'
                sh 'gradle build'
                sh 'gradle bootRun'
            }
        }
        stage('Test'){
            steps{
                echo 'tests'
            }
        }
        stage('Validate'){
            steps{
                echo 'validate'
            }
        }            
        stage('Deploy'){
            steps{
                echo 'deploy'
            }
        }


        }    
    }
