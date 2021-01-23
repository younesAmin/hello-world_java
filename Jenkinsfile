node {
    stage('clone') {
    git 'https://github.com/younesAmin/hello-world_java.git'
    }
    stage('build') {
    sh 'javac main.java'
    }
    stage('run') {
    sh 'java main'
    }
}

