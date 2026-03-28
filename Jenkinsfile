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

	currentBuild.result == 'FAILURE'
	
	stage('login with Map') {
		log.error(name:"anas", age: 31)
	}
	echo currentBuild.result
	stage('login with Map') {
		customNode()
	}

}


