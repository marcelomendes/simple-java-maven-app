node {
    docker.withServer('tcp://docker:2376', 'docker-credentials') {
        docker.image('maven:3-alpine').withRun('-v /root/.m2:/root/.m2') {

        }
    }
}
