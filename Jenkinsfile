pipeline {
    agent {label 'MASTER'}
    stages {
        stage('Source'){
            steps {
                git 'https://github.com/dummyrepos/spring-petclinic.git' 
            }
        }
        stage('Package'){
            steps {
                sh 'mvn package'
            }
        }
    }
}
