pipeline{
    agent any
    
    stages{
        stage("Build"){
            steps{
                echo "Stage 1: Build the code"
                echo "Using Maven for code automation"
                }
            }
        stage("Unit and Integration Tests"){
            steps{
                echo "Stage 2: Run Unit tests to ensure code functions"
                echo "Running unit and integration tests"
            }
        }
        stage("Code Analysis"){
            steps{
                echo "Stage 3: Code Analysis"
                echo "Utilising SonarQube for code quality tests"
            }
        }
        stage("Security Scan"){
            steps{
                echo "Stage 4: Security Scan"
                echo "Utilising OWASP ZAP for security scans"
            }
        }
        stage("Deploy to Staging"){
            steps{
                echo "Stage 5: Deploy to Staging"
                echo "Staging to staging server AWS EC2"
            }
        }
        stage("Integration Tests on Staging"){
            steps{
                echo "Stage 6: Integration Tests on Staging"
                echo "Running integration tests on staging environment"
            }
        }
        stage("Deploy to Production"){
            steps{
                echo "Stage 7: Deploy to Production"
                echo "Deploying to production server AWS EC2"
            }
        }
    }
}