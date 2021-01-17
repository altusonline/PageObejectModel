pipeline{
agent any
		stages{
			stage('Build'){
				steps{
					echo "Building"
				}
			}
			stage('Deploy to QA'){
				steps{
					echo "Deployed to QA Env"
				}
			}
			stage('Test on QA'){
				steps{
					echo "Testing in QA Env"
				}
			}
			stage('Deploy to Stage'){
				steps{
					echo "Deploying to Stage Env"
				}
			}
			
			stage('Test to Stage'){
				steps{
					echo "Testing in Stage Env"
				}
			}
			
			stage('Release'){
				steps{
					echo "Production Release"
				}
			}
			
			stage('Monitor'){
				steps{
					echo "Monitoring Production"
				}
			}
		}
}