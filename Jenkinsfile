node() {
	ws('/var/jenkins_home/workspace/Gradle@2 '){
	stage('Source'){
		git url: 'https://github.com/LengLee/TestingJenkinsGradle'
	}
	stage('Compile'){
		sh "./gradlew clean compileJava"
	}
	stage('Run'){
		sh "./gradlew run "
	}
	}
}

