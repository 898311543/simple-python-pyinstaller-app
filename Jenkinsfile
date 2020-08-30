pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                windows_node
            }
            steps {
                python -m py_compile sources/add2vals.py
            }
        }
    }
}