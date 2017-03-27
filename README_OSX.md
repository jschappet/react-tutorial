#Running React-Tutorial with LaunchControl


    cp local.react-tutorial.plist /Library/LaunchDaemons/local.react-tutorial.plist
    sudo launchctl load -w /Library/LaunchDaemons/local.react-tutorial.plist 
    sudo launchctl start local.react-tutorial
