pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        echo "git pipeline"
        sh 'mvn clean install'
      }
    }
    stage('execute'){
      steps{
        echo "another stage"
      }
    }
  }
}
