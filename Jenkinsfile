@Library('common') _

pipeline {
    agent any

    stages {
        stage ('Info') {
		    steps {
		        script {
		    	    common.info("Its just an info")
		        }
		    }
		}
		stage ('Warning') {
		    steps {
		        script {
		    	    common.warning("This is a warning")
		        }
		    }
		}
    }
}
