pipeline{
    agent any
    stages{
        stage('1-my name'){
            steps{
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
        stage('4-fourth name'){
            steps{
                echo "my name is Lateef"
                sh 'ps -ef'
            }
        }
        stage('5-fifth name'){
            steps{
                echo "my name is Annick"
                sh 'ps -ef'
            }
        }
        stage('6-sixth name'){
            steps{
                echo "My name is Frank"
                sh 'ps -ef'
            }
        }
        stage('7-seventh name'){
            steps{
                echo "my name is Bukola"
                sh 'ps -ef'
            }
        }
       stage('8-eighth'){
	steps{
		echo "my name is francisca"
		sh 'ps -ef'
	    }
      } 
    }
	post {
        // Clean after build
        always {
            cleanWs(cleanWhenNotBuilt: false,
                    deleteDirs: true,
                    disableDeferredWipeout: true,
                    notFailBuild: true,
                    patterns: [[pattern: '.gitignore', type: 'INCLUDE'],
                               [pattern: '.propsfile', type: 'EXCLUDE']])
        }
    }
}

