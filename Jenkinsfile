pipeline {
	agent {
    		label 'linux'
	}
    stages {
        stage('Build on k8 ') {
            steps {           
                        sh 'pwd'
                       // sh 'cp -R helm/* .'
		        sh 'ls -ltr'
                        sh 'pwd'
                        sh '/usr/local/bin/helm install petclicnic-app helm/petclinic'
              			
            }           
        }
    }
}
