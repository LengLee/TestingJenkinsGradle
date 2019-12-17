node() {
	def workspace = pwd()
	print 'workspace'
	
	sh ' echo ${WORKSPACE} '
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

