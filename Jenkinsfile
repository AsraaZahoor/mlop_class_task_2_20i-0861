pipeline {
    agent any
    
    stages {
        stage('Clone') {
            steps {
                // Checkout repository
                git 'https://github.com/AsraaZahoor/mlop_class_task_2_20i-0861'
            }
        }
        
        stage('Dependencies') {
            steps {
                // Install dependencies
                sh 'pip3 install -r requirements.txt'
            }
        }
        
        stage('Testing') {
            steps {
                // Run tests
                sh 'pytest test.py'
            }
        }
        
        stage('Deployment') {
            steps {
                // Dummy deployment
                script {
                    if (env.BRANCH_NAME == 'main') {
                        // Deploy to production
                        echo 'Deploying to production...'
                       
                    } else {
                        // Deploy to staging or any other environment
                        echo 'Deploying to staging...'
                        // Add your deployment commands here
                    }
                }
            }
        }
    }
}
