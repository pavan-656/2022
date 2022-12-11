pipeline {
          agent { 
              node {
		           label '2'
				   customWorkspace "/home/ec2-user/job-11"
				   }
          }
				   stages {
				   stage ('parallel-stage') {
				   parallel {
				           stage ('stage-1') {
						   steps {
						   echo "good morning"
						           }
								   }
								   stage ('stage-2') {
						   steps {
						   echo "good evening"
						           }
								   }
								   stage ('stage-3') {
						   steps {
						   echo "good night"
						           }
								   }
								   }
								   }
								   stage ('sequential-1') {
								   steps {
								   sh "sudo mkdir sequential-11"
								   
								   }
								   }
								   stage ('sequential-2') {
								   steps {
								   sh "sudo mkdir sequential-12"
								   
								   }
								   }
								   }
								   }
								   
								 
