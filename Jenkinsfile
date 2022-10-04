pipeline{
    agent any
	options {
        // This is required if you want to clean before build
        skipDefaultCheckout(true)
    }
    stages{
        stage('1-my name'){
            steps{
		    cleanWs()
                // We need to explicitly checkout from SCM here
                checkout scm
                echo "Building ${env.JOB_NAME}..."
                echo "My name is Abayomi"
                sh 'ps -ef'
            }   
        }
       stage('2-second name'){
            steps{
                echo "My name is Claudi-ann"
                sh 'ps -ef'
            }
        }
	stage('3-third name'){
            steps{
                echo "My name is abbey"
                sh 'ps -ef'
            }
        }
    }
}

