pipeline{
  agent any
  tools{
    maven 'maven1'
  }
  stages{
    stage('build'){
      steps{
        echo "git pipeline"
        sh 'mvn clean '
      }
    }
    stage('execute'){
      steps{
        echo "another stage"
      }
    }
  }
}
