@Library('jenkins-shared-library') _

def configmap = [
    project: "expense"
    component: "backend"
]

if( ! env.BRANCH_NAME.equalsIgnoreCase('main')){  //true , if branch is Feature branch
    nodeJSEKSPipeline(configmap)
}
else{
    echo "Follow the process of PROD release"
}