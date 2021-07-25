pipeline{
   agent {
    node {
      label 'assessment_node'
    }
  }
    
      stage('Test'){
          steps{
          sh 'mvn test'
          }
      }
      stage('Build'){
          steps{
          sh 'mvn install'
          }
      }
      stage('Deploy'){
          steps{
          sh 'mvn deploy'
          }
      }
      
    }
}
