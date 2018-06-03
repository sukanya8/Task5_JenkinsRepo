pipeline{
agent any

properties([
    pipelineTriggers([
      [$class: "GitHubPushTrigger"]
    ])
  ])


stages{
    
   stage('Build'){
     steps{
          echo 'Building...'
	  }
      
     }
     stage ('Test') {
     steps{
          echo 'Testing..'
	  }
	  }
	  stage('Deploy') {
	  steps{
	  echo 'Deploying...'
	  }
	  }
	  }
	  }
