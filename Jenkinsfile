//Jenkinsfile (Scripted Pipeline)
node {
    checkout scm 
    stage('build building container') {
    		sh 'docker build -t -f dockerfile'
    }
}
