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
                bat 'python -m py_compile sources/add2vals.py'
            }
        }
    }
}