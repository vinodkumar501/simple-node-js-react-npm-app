node {

    stage('Initialize')
    {
        def dockerHome = tool 'docker'
        def mavenHome  = tool 'mvn'
        env.PATH = "${dockerHome}/bin:${mavenHome}/bin:${env.PATH}"
    }

    stage('Checkout') 
    {
        checkout scm
    }
}
