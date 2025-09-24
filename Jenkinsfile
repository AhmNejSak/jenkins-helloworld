node {
    stage('clone') {
        git branch: 'main', credentialsId: 'cred', url: 'git@github.com:AhmNejSak/jenkins-helloworld.git'
    }
    stage('build') {
        sh '''javac Main.java'''
    }
    stage('run') {
        sh '''javac Main.java'''
    }
}
