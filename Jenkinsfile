pipeline {
agent any
tools{
  maven 'maven'
}
stages{
    stage("build"){
      steps{
        echo "build completed..."
        sh 'mvn install'
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


      
  
