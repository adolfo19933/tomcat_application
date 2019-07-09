node {
    def app

    stage('Clone repository locally') {
        /* Let's make sure we have the repository cloned to our workspace */

      stage 'enter commit id'
def userInput = input(
 id: 'enter commit id', message: 'select a commit id', parameters: [
 [$class: 'commit id', defaultValue: '', description: 'enter commit id', name: 'commit id']
])
echo ("commit id: "+userInput)
}