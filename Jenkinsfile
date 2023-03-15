pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                if(env.BRANCH_NAME == master )
                {
                    echo 'Deploying.... from master branch '
                }
                
                else
                {
                    echo 'This branch does not have deployment'
                }
                    
            }
        }
    }
}
