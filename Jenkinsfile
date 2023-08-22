pipeline{
  agentany

  triggers{
    githubPush()
  }
  stages{
    stage("Checkout"){
      steps{
        checkout scm
      }
    }
  }
}
