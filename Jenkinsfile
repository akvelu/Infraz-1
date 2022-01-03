pipeline
{
  agent any
  stages {
    stage ("git checkout") {
      steps {
      git 'https://github.com/vignesh2612/Infraz.git'
    }
          }
    stage ("maven build") {
      steps {
      bat '''mvn clean install
      }
      }
      }
      }
      
  
