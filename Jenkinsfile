node() {
	stage('Source'){
		git url: 'https://github.com/LengLee/TestingJenkinsGradle'
	}
	stage('Compile'){
		sh "./gradlew clean compileJava"
	}
}

