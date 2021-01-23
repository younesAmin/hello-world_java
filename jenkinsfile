node {
	stage('clone') {
	git 'https://github.com/younesAmin/hello-world_java.git.git'
	}
	stage('build') {
	sh label: '', script: 'javac main.java'
	}
	stage('run'){
	sh label: '', script: 'java main'
	}
}

