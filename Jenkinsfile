pipeline {
		agent {
		node {
		label ('built-in')
			}
		}
		stages {
		stage ('install-httpd1') {
			steps {
			sh "yum install httpd -y"
			}
			}
			stage ('install-tree') {
			steps {
			sh "yum install tree -y"
			}
			}

	
	}


}
