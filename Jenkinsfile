pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // Get some code from a GitHub repository
             //   git url: 'https://github.com/joeilan/HOTP_JPetStore.git', branch: 'master'
               step([$class: 'RTWProductHelper', configfile: '', exportReportFileName: '', exportReportFolder: '', exportReportFormat: '', exportReportType: 'unified', exportReportUsage: false, exportstatreportlist: '', exportstats: '', exportstatsformat: '', exportstatshtml: '', imports: '', imsharedloc: '', labels: '', name: 'HOTUI_JPetStore', overwrite: 'true', project: 'JPetStore', protocolinput: '', publish: '', publishfor: '', publishreports: '', quiet: 'false', results: '', suite: 'Tests\\01_Login_JPetStore.testsuite', swapdatasets: '', usercomments: '', varfile: '', vmargs: '', workspace: 'C:\\OT_Workspace\\HOTUI'])
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
