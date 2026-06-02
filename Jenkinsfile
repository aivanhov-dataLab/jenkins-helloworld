node {
    stage('clone') {
        git 'https://github.com/aivanhov-dataLab/jenkins-helloworld.git'
}
    stage('build') {
        sh 'javac Main.java'
}
    stage('run') {
        sh 'java Main'
}
}
