
pipeline {
agent any
  stages{
    stage('build'){ 
      step {
        sh '/home/vagrant/maven3/bin/mvn clean install'
      }
    }
  }
}
