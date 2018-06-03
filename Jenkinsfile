pipeline{
agent any

properties([
    pipelineTriggers([
      [$class: "GitHubPushTrigger",git credentialsId: '88cc4a1d-32a4-4d74-b830-bef4b5292311', url: 'https://github.com/sukanya8/Task5_JenkinsRepo.git']
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
