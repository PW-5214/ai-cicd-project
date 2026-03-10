pipeline {
 agent any

 stages {

 stage('Pull Code') {
 steps {
 git 'https://github.com/pw-5214/ai-cicd-project.git'
 }
 }

 stage('Deploy to Kubernetes') {
 steps {
 sh 'kubectl apply -f deployment.yaml'
 }
 }

 }

}
