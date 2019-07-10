pipeline {
    agent any
    stages {
        stage('Select commit id') {
            input {
                message "ENTER COMMIT ID"
                ok "Continue to deploy"
                submitter "USER"
                parameters {
                    string(name: 'COMMIT_ID', defaultValue: '', description: 'Which commit id should i deploy?')
                }
            }
            steps {
                echo "You have selected commit id, ${COMMIT_ID} "
                if($COMMIT_ID) == null {

                    echo "no entry entered"
                }
            }
        }
    }
}