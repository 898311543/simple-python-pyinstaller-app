pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
				node{ 
					label 'windows_node'
					}
            }
            steps {
                bat 'pyinstaller sources/add2vals.py'
            }
        }
    }
}