
node('master'){
  
  stage('checkout') {
    checkout([$class: 'GitSCM', branches: [[name: '**']], doGenerateSubmoduleConfigurations: false, extensions: [[$class: 'CleanBeforeCheckout']], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/devopsolluri2/samplerepo2.git']]])
  }
  
   stage('Build') { 
     echo 'Build stage '    
   }
}

   
