pipeline{
 agent any  //没有指定agent
    stages{
        stage('deploy to test1'){
		when {
		    branch 'master'
		}
		steps {
		   echo "deploy to test env"
		   echo "this is master branch and need to test"
		}
        }
	stage('deploy to prod'){
		when {
		    branch 'release'
		}
	    steps{
		  echo "deploy to prod env"
	   }


	}	
    }
}
