node {
    properties([
       //pipelineTriggers([pollSCM('0 * * * *')]),
       parameters([
           string(defaultValue: 'John Snow', description: "Who knows nothing?", name: "NAME")
       ])
    ])
    checkout scm
    stage("Say Hi") {
        echo params.NAME
    }
}
