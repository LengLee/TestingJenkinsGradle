node() {
	stage('Source'){
		git url: 'https://github.com/LengLee/TestingJenkinsGradle'
	}
	stage('Compile'){
		sh "gradle clean compileJava"
	}
}

