@Library('my-lib') _

node {
	// library 'my-lib'
	stage('initialisation') {
		log()
	}
	
	stage('login with params') {
		log.info("staiwa")
	}

	if(currentBuild.result == 'SUCCESS'){
		echo "yaaaaaaaaaaaaaaay ###"
	}
	stage('login with Map') {
		log.error(name:"anas", age: 31)
	}

	stage('login with Map') {
		customNode()
	}

}


