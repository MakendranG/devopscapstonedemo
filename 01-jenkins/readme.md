Job 1 - Snake


cd /root/snake-multiplayer/
npm install
npm start &


Job 2 -  snake-git integration


git integrated

Job 3 - snake-pipeline


node {
    // some block
    

dir('snake-multiplayer') {
    // some block

stage('Git Checkout') {
    // some block
    git branch: 'main', url: 'https://github.com/MakendranG/devopscapstonedemo.git'
}




stage('Application Deployed') {
    // some block
    sh 'npm install'
}





stage('Application Started') {
    // some block
    sh 'npm start &'
}







}



}

