node{
	stage('CHECKOUT') {
		callGithub.checkoutRepo()
	}
	stage("Run Tests") {
    sh '''
        echo "Its Develop branch, hence skipping runtest"
        exit 0
    '''
	}
}
