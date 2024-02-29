pipeline {
    agent any
    
 
    stages {


 parameters {
   
    	string(name:'BranchName',
      	defaultValue: 'master!',
      	description: 'enter your branch name')
  }
        stage('build th app'){ 
            steps {
            sh 'mvn clean '
             echo 'Test for Tah'
                
            }
        }
    }
}