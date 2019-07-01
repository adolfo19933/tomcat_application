node {
    def app

    stage('Clone repository locally') {
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
    }

    stage('execute shell commands') {

        sh /scripts/hello.sh


    }
}