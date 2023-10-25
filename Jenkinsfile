pipeline {
    agent any

    stages {
        stage('list out the images') {
            steps {
                script {
                    // json='$(curl -s -u UcfvXPtlbX:x93752H0jS4f618s -X GET https://7tiuxysa.c1.gra9.container-registry.ovh.net/api/v2.0/projects/mydemoproject/repositories/frontend/artifacts?)'
                    // echo $json | grep -o '"name":"[^"]*' | grep -o '[^"]*$'
                    // echo $json | grep -o '"name":"[^"]*'
                    sh 'curl -s -u UcfvXPtlbX:x93752H0jS4f618s -X GET https://7tiuxysa.c1.gra9.container-registry.ovh.net/api/v2.0/projects/mydemoproject/repositories/frontend/artifacts?'
                }
            }

        }
        
    }   
}
