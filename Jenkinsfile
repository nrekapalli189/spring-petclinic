node{
    stage('GitClone'){
        git '-b main https://github.com/nrekapalli189/spring-petclinic.git'
    }
    stage('Maven'){
        sh 'mvn clean package'
    }
    stage('archival'){
         archive 'target/*.jar'
    }
}
