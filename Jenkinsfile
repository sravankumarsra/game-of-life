pipeline{
        agent {label 'jdk8'}
        stages{
          stage('Build the code'){
                steps{
                git 'https://github.com/sravankumarsra/game-of-life.git'
                }
                }
          stage('Build package'){
                steps{
                sh 'mvn clean'
                }
                }
        }
}
