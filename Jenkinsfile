node
{
    stage('Starting')
    {
        echo 'I am starting from here'
    }
    stage('CheckOut')
    {
        git 'https://github.com/AshutoshKumar99/TVS'
        
    }
    
    stage('archive Artifacts')
    {
        archiveArtifacts '**/*.java'
    }
    
    stage('Laptop')
    {
        echo 'Dell Vostro 2520'
    }
    
    stage('Building Job Exx')
    {
        build 'Exx'
    }
    
}