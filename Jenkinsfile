node {
    stage('Checkout Code') {
        // Clone the repo from GitHub (make sure "main" is your actual branch)
        git branch: 'main', url: 'https://github.com/IslamSidratul/DevOps-module-02-project-1.git'
    }

    stage('Read and Output hello.txt') {
        // Read the file and print its contents to the build log
        def content = readFile('hello.txt')
        echo "Contents of hello.txt:\n${content}"
    }
}
