pipeline{
  agent any
  stages{
    stage('install'){
      steps{
        bat 'npm install'
      }
    }
    stage('build'){
      steps{
        bat 'npm run build'
      }
    }
    stage('run'){
      steps{
        bat 'npm run dev'
      }
    }
  }
}
