pipeline{
//agent any
    agent any
    stages{
    	stage('Build jar'){
    		steps{
    			sh "mvn clean package -DskipTests"
    		}
    	}
    }

}


