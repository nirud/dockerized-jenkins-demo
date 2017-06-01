node {
    stage('Checkout SCM') {
        checkout scm
    }

    stage('Build') {
        sh './gradlew clean assemble'
    }
}
