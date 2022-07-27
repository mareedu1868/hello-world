pipeline {
agent any
  stages{
    stage("build"){
      steps{
        echo "build completed..."
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


      
  
