node {
      stage ('git clone') {
            git 'https://github.com/shankarchaya/jenkins.git'
            }
      stage('mvn clean') {
            bat 'mvn clean'
            }
      stage('mvn validate') {
            bat 'mvn validate'
            }
      stage('mvn compile') {
            bat 'mvn compile'       
            }
      stage('mvn test') {
            bat 'mvn test'
            }
      stage('mvn package') {
            bat 'mvn pacakge'
             }
}
    
