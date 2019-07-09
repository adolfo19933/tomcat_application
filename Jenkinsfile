pipeline {
    agent any
    stages {
        stage('Select commit id') {
            input {
                message "ENTER COMMIT ID"
                ok "Continue"
                submitter "USER"
                parameters {
                    string(name: 'COMMIT_ID', defaultValue: 'Enter commit id here', description: 'Which commit id should i deploy?')
                }
            }
            steps {
                echo "You have selected commit id, ${COMMIT_ID} "
            }
        }
    }
}