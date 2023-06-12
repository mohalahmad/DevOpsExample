pipeline {
    agent { node { label 'vm1' } }

    stages {
        stage('Test') {
            steps {
                /* `make check` returns non-zero on test failures,
                * using `true` to allow the Pipeline to continue nonetheless
                */
                echo "hi"
            }
        }
    }
}