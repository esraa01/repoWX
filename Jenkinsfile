pipeline{
  agent none
  stages{
    stage('A'){
      parallel{
        stage('Welcome'){
          agent none
          steps{
            echo "Esraa"
          }
        }
        stage('B'){
          agent none
          steps{
            echo "Welcome"
          }
        }
      }
  }
}
