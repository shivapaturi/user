@Library('jenkins-shared-library@main') _

def configMap = [
    project: "roboshop",
    component: "user"
]

if (!env.BRANCH_NAME.equalsIgnoreCase('main')) {
    nodejsEKSPipeline(configMap)
} else {
    echo "Please proceed with PROD process"
}