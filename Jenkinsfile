pipeline {
    agent any

    stages {
        stage('list out the images') {
            steps {
                script {
                    
                    // sh 'curl -s -u UcfvXPtlbX:x93752H0jS4f618s -X GET https://7tiuxysa.c1.gra9.container-registry.ovh.net/api/v2.0/projects/mydemoproject/repositories/frontend/artifacts?'
                    def json = sh 'curl -s -u UcfvXPtlbX:x93752H0jS4f618s -X GET https://7tiuxysa.c1.gra9.container-registry.ovh.net/api/v2.0/projects/mydemoproject/repositories/frontend/artifacts?'
                        for (img in json.split(",")) {
                            println("${img}")
                        }
                }

            }
        }

    }
        
}