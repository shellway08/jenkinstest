pipeline{
    agent any
    stages{
        stage('环境'){
            steps{
                echo "环境监测"
                sh 'printenv'

            }
        }
        stage('编译'){
            steps{
                echo "编译"
            }
        }
        stage('测试'){
            steps{
                echo "测试"
            }
        }
        stage('打包'){
            steps{
                echo "打包"
            }
        }
        stage('部署'){
            steps{
                echo "部署"
            }
        }
    }
}