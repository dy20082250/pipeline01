pipeline{
 agent any  //没有指定agent
    stages{
        stage('checkout code'){
            steps{
                sh 'echo "checkout code"'a
		git clone git@github.com:dy20082250/pipeline01.git
            }
        }
	stage('build'){
	    steps{
		sh "ifconfig ens33"
	   }
	}	
    }
}
