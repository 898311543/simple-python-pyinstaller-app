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
                sh 'pyinstaller -F sources/add2vals.py -w'
            }
        }
    }
}