pipeline{
 agent any  //没有指定agent
    stages{
        stage('checkout code'){
            steps{
                sh 'echo "checkout code"'
            }
        }
	stage('build'){
	    steps{
		sh 'echo test2'
		sh 'free -m'
		sh 'ansible --version'
		sh 'ansible-playbook --version'
	   }


	}	
    }
}
