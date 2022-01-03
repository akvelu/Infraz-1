pipeline
{
  agent any
  stages {
    stage ("git checkout"){
      steps {
      git 'https://github.com/vignesh2612/Infraz.git'
    }
          }
    stage {
      steps {
        ("maven build")
      bat '''mvn clean install
      }
      }
      
  
