#!/usr/bin/env groovy


node('docker') {


//try{
  stage('Checkout from Git') {
    // No special needs here, if your projects relys on submodules the checkout step would need to be different
    checkout scm
  }

  stage('Run new Container') {
    sh 'pwd'
    }

//}catch (any) {
  //emailext (
    //       subject: "Error: Job '${env.JOB_NAME} [${env.BUILD_NUMBER}]'",
      //     body: """Error: Job '${env.JOB_NAME} [${env.BUILD_NUMBER}]'""",
        //   recipientProviders: [[$class: 'DevelopersRecipientProvider']],
          // to: ''
         //)
//}finally {
  //emailext (
    //       subject: "Success: Job '${env.JOB_NAME} [${env.BUILD_NUMBER}]'",
      //     body: """Success: Job '${env.JOB_NAME} [${env.BUILD_NUMBER}]'""",
        //   recipientProviders: [[$class: 'DevelopersRecipientProvider']],
          // to: ''
//
  //       )
//}

}