echo "Hello DB" 
node{
  stage('checkout'){
		steps{     
		   git branch : 'main', credentialid:'e5a4adda-8639-4cd8-9700-2d68d09bc50c',
		   url: 'https://github.com/lpv1990/Databricksdemo.git'
	   }
       
  }
  stage ('Build') {
		steps {
			bat 'echo Hello Build stage'
			//bat 'mkdir C:\\Db-jenkins-tesst'
		}
	} 
}
