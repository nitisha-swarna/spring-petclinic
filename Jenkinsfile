node {
    stage('scm'){
        git 'https://github.com/dummyrepos/spring-petclinic.git'
    }

    stage('build'){
        sh 'mvn package'
    }
}