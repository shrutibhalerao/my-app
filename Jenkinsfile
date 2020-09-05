
node {
   // This is to demo github action	
 
  stage('SCM Checkout'){
    // Clone repo
	git 'https://github.com/shrutibhalerao/my-app/edit/master/Jenkinsfile'
	
  
   }
   
  stage('compile-Package'){
   def mvnHome = tool name: 'maven3', type: 'maven' 
   sh "${mvn} clean package deploy"
  }
   
 

}

