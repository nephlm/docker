* Composerize: Turn docker run command to docker-compose.yml file
    * https://www.composerize.com/
    
* Runlike: Get run command from running container
    * docker run --rm -v /var/run/docker.sock:/var/run/docker.sock assaflavie/runlike [container name]
 

* When windows reboots:
   * Make sure wsl is up first, then start docker desktop
   * Ensure resouces/wsl integration is turned on
   * Maybe that will work, if not you'll probably have to reboot again
