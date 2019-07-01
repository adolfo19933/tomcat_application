node {
    def app

    stage('Clone repository locally') {
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
    }

    stage('execute shell commands') {
                 echo 'Running bat scripts'
                 bat "C:\\Program Files (x86)\\Jenkins\\jobs\\Build-app\\workspace\\scripts\\hello"

    }
}