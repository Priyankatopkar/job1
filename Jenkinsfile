pipeline {
		agent {
		node {
		label ('172.31.37.231')
			}
		}
		stages {
		stage ('install-httpd') {
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
