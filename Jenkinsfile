pipeline {
agent any
  stages{
    stage("build"){
      steps{
        echo "build completed..."
        sh 'git https://github.com/mareedu1868/hello-world.git'
      }}
    stage("test"){
      steps{
        echo "testing completed..."
        sh 'mvn clean install'
      }}
    stage("deploy"){
      steps{
        echo "deploy completed..."
      }}
  }
}


      
  
