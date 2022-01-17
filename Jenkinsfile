pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Build starting'
            }
        }

        stage('Run Tests'){
        steps {
	echo 'Starting DAI Runner...'
	    sh 'chmod +x DAIhrunner'
            sh './DAIrdfefwwefunner -v testcase http://10.211.55.5:8000/ anthony.bianay@keysight.com Dounobichon971! TC_Demo_123 anthony.bianay@keysight.com DEMO_SAP AnthonyLocal /Users/anbianay/Documents/Demo/SAPDemo2.suite'
        }
    }
    
}
}
