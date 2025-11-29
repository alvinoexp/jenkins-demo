// Very simple scripted pipeline to prove everything works

node {

    stage('Checkout') {

        checkout scm

    }


    stage('Build') {

        echo "Hello from Jenkins (scripted pipeline)"

        sh '''

            echo "Running on: $(hostname)"

            git --version || echo "git not found in PATH?"

            ls -R

        '''

    }

}

