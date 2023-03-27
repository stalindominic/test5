pipeline {
    agent any
    environment {
        PATH = "/home/ec2-user/.local/bin:/home/ec2-user/bin:/usr/local/bin:/usr/bin:/usr/local/sbin:/usr/sbin:/opt/apache-maven-3.9.0:/opt/apache-maven-3.9.0/bin://usr/lib/jvm/java-11-amazon-corretto.x86_64/bin"
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
