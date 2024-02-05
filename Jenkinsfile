
echo "Hello DB" 
node{
  stage('checkout'){
     
       git branch : 'main', credentialid:'e5a4adda-8639-4cd8-9700-2d68d09bc50c',
       url: 'https://github.com/lpv1990/Databricksdemo.git'
        
  }
  stage('Build'){
     
       bat 'echo Hello Build stage'
        
  }
  stage('Deploy'){
     
       bat 'echo Hello deploy stage'
       bat 'C:\\Users\\l.prasanna.velaga\\AppData\\Local\\Programs\\Python\\Python311\\Scripts\\databricks.exe workspace import_dir "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\jenkinsdemo\\demoone" /Shared/lakshmiDBdemo'
        
  }
}
