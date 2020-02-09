pipeline{
 agent any  //没有指定agent
    stages{
        stage('checkout code'){
            steps{
                sh 'echo "checkout code"'
		git  url:'git@github.com:dy20082250/pipeline01.git'
            }
        }
	stage('build'){
	    steps{
		sh 'free -m'
		sh 'ansible --version'
		sh 'ansible-playbook --version'
	   }


	}	
    }
}
