
	agent { docker 'centos:centos7' }
	stages {
		stage('First stage') {
			steps {
				sh 'yum install telnet'
				echo 'yum install telnet command has been run'
				echo 'this is a change'
			}
		}
	}
