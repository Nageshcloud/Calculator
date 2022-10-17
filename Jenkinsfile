pipeline{
    agent any 
    stages {
        stage ("SCM") {
            steps{
                git branch: 'master',
                url: 'https://github.com/Nageshcloud/Calculator.git'
            }
        }
        stage ("Build") {
            steps {
                   sh 'mvn clean package'
            }
        }
    }
}
