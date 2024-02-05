node {
  def GITREPOREMOTE = "https://github.com/lpv1990/Databricksdemo.git"
  def GITBRANCH     = "main"
  def DBCLIPATH     = "C:\Users\l.prasanna.velaga\AppData\Local\Programs\Python\Python311\Scripts\"
  def JQPATH        = "C:\Users\l.prasanna.velaga\AppData\Local\Programs\Git\usr\bin\jq.exe"
  //def JOBPREFIX     = "<job-prefix-name>"
  def BUNDLETARGET  = "/Shared/lakshmiDBdemo"
 
  stage('Checkout') {
    git branch: GITBRANCH, url: GITREPOREMOTE
  }
  
 }
