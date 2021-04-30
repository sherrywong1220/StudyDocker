1. 在 terminal 输入 screen ~/Library/Containers/com.docker.docker/Data/com.docker.driver.amd64-linux/tty
2. You should see a blank screen, just press Enter , and after a while, you should see a command line prompt
3. Now you're inside Docker's VM and you can cd into volumes dir by typing: cd /var/lib/docker/volumes
4. Profit, you got there!
5. If you need to transfer files from your MacOS host into Docker host (for example to put files into docker volumes) use directories shared between host (mac os) and Docker host (Docker VM), you can find a list of such directories under File Sharing tab of your Docker for Mac application.
