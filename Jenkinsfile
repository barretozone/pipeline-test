@Library('Jenkins Shared lib') _

node {
    stage('Setup') {
        testHello message: 'Test'
    }
    stage('Read File') {
        def content = readFile "config.json"
        println($content)
    }
}
