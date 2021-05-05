pipeline {	 
	agent any	
    	stages {     	 
    	stage("Compile") {          	 
            	steps {               	 
                	sh "/Users/nagen/Documents/compilejava.sh"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	sh "java HelloWorld"          	 
            	}     	 
        	}	 
    	}
}
