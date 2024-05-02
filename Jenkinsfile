pipeline{
    agent any
    stages {
        stage('Build') {
            steps{
                echo "Build started and completed"
            }
            post{
                success{
                    mail to: "sathiyanarayanan.test@gmail.com",
                    subject: "Build successful",
                    body: "send check email"
                }
            }

        }
        stage('Test') {
            steps{
                echo "Test started and completed"
            }
        }
        stage('Deploy') {
            steps{
                echo "Deploy started and completed"
            }
        }
    }
} 
