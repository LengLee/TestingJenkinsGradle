node() {
	stage('Source'){
		git url: 'https://github.com/LengLee/NewBangkok-web'
	}
	stage('Compile'){
		sh "gradle clean compileJava"
	}
}

