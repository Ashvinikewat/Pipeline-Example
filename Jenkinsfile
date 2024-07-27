pipeline{
    agent any
    stages{
        stage("compile"){
            steps{
                echo 'javac HelloWorld.java'
            }
        }
        stage("run"){
            steps{
                echo "java HelloWorld"
            }
        }
    }
}