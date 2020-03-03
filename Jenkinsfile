pipeline {
    environment {
        registry = "continuouslee/real-world-backend"
        registryCredential = "dockerhub"
        dockerImage = ""
    }
    agent any
    tools {
        gradle 'gradle621'
        jdk 'jdk8'
    }
}