pipeline{
    agent any
    stages{
        stage("compile"){
            steps{
                batch 'javac HelloWorld.java'
            }
        }
        stage("run"){
            steps{
                batch "java HelloWorld"
            }
        }
    }
}