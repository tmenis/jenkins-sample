// Powered by Infostretch 

timestamps {

node () {

	stage ('App-IC2 - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'git-login', url: 'https://github.com/tmenis/jenkins-sample']]]) 
	}
}
}