/* Cloning the git branch*/
stage('Clone repository') {
        checkout scm
}
/* Start docker-compose with five instances of Chrome */
stage('Start docker-compose') {	
	sh 'docker-compose up -d --scale chrome=5 --scale firefox=0'
}
