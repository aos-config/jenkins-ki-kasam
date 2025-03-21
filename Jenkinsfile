pipeline{
  agent any

  environment{
    Dockerimage = "my-docker:20"
  }
  stages{
    stage('build docker image with Dockerfile'){
      steps{
        
        bat "docker build -t %Dockerimage% ."
        bat "The image is build"
        
      }
    }
  }
}
