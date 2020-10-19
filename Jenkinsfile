pipeline{
 agent any  //没有指定agent
    stages{
        stage('deploy to test'){
		when {
		    branch 'master'
		}
		steps {
		   echo "deploy to test env"
		}
        }
	stage('deploy to prod'){
		when {
		    branch 'release'
		}
	    steps{
		  echo "deploy to prod env"
		  echo "this is release branch and need to test"
	   }


	}	
    }
}
