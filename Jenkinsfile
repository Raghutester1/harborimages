pipeline {
    agent any
    
    stages {
        stage('list out the images') {
            steps {
                script {
                    // sh 'curl -s -u UcfvXPtlbX:x93752H0jS4f618s -X GET https://7tiuxysa.c1.gra9.container-registry.ovh.net/api/v2.0/projects/mydemoproject/repositories/frontend/artifacts?'
                    sh 'curl -s -u UcfvXPtlbX:x93752H0jS4f618s -X GET https://7tiuxysa.c1.gra9.container-registry.ovh.net/api/v2.0/projects/mydemoproject/repositories/frontend/artifacts? | jq -r \'.name\'', returnStdout: true.trim()

                        
                }

            }
        }

    }
        
}