#!groovy
@Library('sharedlibrary')_

st_pipeline_ci([
 git_url: 'https://github.com/jenkins-docs/simple-java-maven-app.git',
 git_branch: 'master',
 mvnPath: 'pom.xml'
])







//def checkout  = new checkout()
//checkout
//([
//mvnPath: "/usr/path"
//])

/*test = """
apiVersion: "v1"
kind: "Pod"
spec:
  containers:
  - name: node
    image: docker.io/node:latest
    imagePullPolicy: Always
    command:
    - cat
    tty: true
  

  nodeSelector:
    env: jenkins
  restartPolicy: "Never"
  securityContext: {}
  
"""
pipeline {
   agent any
stages{
    
    stage("Checkout"){
        steps{
         //build_ci 'Rizwan'
        // gitCheckout([
         //git_url: "https://github.com/jenkins-docs/simple-java-maven-app.git",
        // git_branch: "master"
         
         //])
          
          my_function([ mvnPath:'pom.xml' ])
        }}
    }
}
*/

