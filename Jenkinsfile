node() {
	stage('Source'){
		git url: 'https://github.com/LengLee/TestingJenkinsGradle'
	}
	stage('Compile'){
		sh "cd /var/jenkins_home/workspace/GradlePipe/TestingJenkinsGradle/HelloWorld"
		sh "gradle clean compileJava"
	}
}

