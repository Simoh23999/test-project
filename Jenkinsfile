@Library('my-lib') _

node {
	// library 'my-lib'
	stage('initialisation') {
		log()
	}
	echo currentBuild.result
	stage('login with params') {
		log.info("staiwa")
	}

	currentBuild.result = 'UNSTABLE'
	
	stage('login with Map') {
		log.error(name:"anas", age: 31)
	}
	echo currentBuild.result
	stage('login with Map') {
		customNode()
	}

	stage('Mailing'){
		mail subject: 'Email Subject', body: 'Email Body Content', to: 'elhadadmohammed665@gmail.com'
	}

}


