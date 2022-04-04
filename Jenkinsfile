pipeline{
 agent any
  Stages{
    stage('compile'){
      steps{
    withMaven(maven:''){
      sh 'mvn clean compile'
                        }
            }
                     }
    stage('test'){
      steps{
    withMaven(maven:''){
      sh 'mvn test'
                        }
            }
                     }
    stage('deploy'){
      steps{
    withMaven(maven:''){
      sh 'mvn deploy'
                        }
            }
                     }
}
}
