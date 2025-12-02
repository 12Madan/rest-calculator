
node{
    stage('scm checkout') {
        git 'https://github.com/12Madan/rest-calculator'
    }
    stage('maven'){
       sh ' mvn clean package'
    }
}
