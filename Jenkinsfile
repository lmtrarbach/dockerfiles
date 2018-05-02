pipeline {
  agent {
    docker {
      image 'jenkinsci/slave'
    }
    
  }
  stages {
    stage('teste') {
      steps {
        mail(subject: 'Teste Jenkins', body: '<html><h1> Teste Jenkins</h1></html>', charset: 'UTF8', from: 'luthiano.trarbach@interop.com.br', to: 'luthiano.trarbach@interop.com.br')
      }
    }
  }
}