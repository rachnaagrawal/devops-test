pipeline{
	agent any
	stages{
		stage('Clone'){
			steps{
				dir("E:\\build_clone"){
					git credentialsId: 'gitcred', url: 'https://github.com/rachnaagrawal/devops-test.git'
				}
			}
		}
		stage('Bootstrap target configuration'){
			steps{
			echo "to be build"
			}
		}
		stage('Set version'){
			steps{
			echo "to be build"
			}
		}
		stage('Munit test'){
			steps{
				bat 'mvn clean install'
			}
		}
		stage('Maven Build and Deploy to Exchange'){
			steps{
				echo "to be build"
			}
		}
	}
}
