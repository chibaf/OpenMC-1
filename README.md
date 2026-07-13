# OpenMC  
https://openmc.org

## Remote jupyter notebook
Running Jupyter Notebook on a remote server — Anaconda documentation  
https://web.archive.org/web/20200628012208/https://docs.anaconda.com/anaconda/user-guide/tasks/remote-jupyter-notebook/  
Running Jupyter Notebook on a remote server¶  
Follow the following steps to use Jupyter Notebook launched from remote server.

1. Launch Jupyter Notebook from remote server using port 8080: jupyter notebook --no-browser --port=8080 Or run the following command to launch with default port: jupyter notebook --no-browser Please note the port setting. You will need it in the next step.  
2. You can access the notebook from your remote machine over SSH by setting up a SSH tunnel. Run the following command from your local machine: ssh -L 8080:localhost:<port> <remote_user>@<remote_host> Note Replace <port> with your port number used in the above step, <remote_user> with remote server username, and <remote_host> with your remote server address.  The above command opens up a new SSH session in the terminal.  
3. Open a browser from your local machine and navigate to http://localhost:8080/, the Jupyter Notebook web interface. Replace 8080 with your port number used in step 1.
  
jupyter notebook --no-browser --port=8080  
  
ssh -L 8080:localhost:8080 chibaf@192.168.150.68
  
http://localhost:8080/

## OpenMC Tutorial | Simulating the Molten Salt Rreactor Experiment  
https://youtu.be/pArhYbZQP0Q?si=OTgjdjELyF_zAoKY  
 via @YouTube   
The Molten Salt Reactor Experiment was a great reactor build and operated successfully in the 1960s. This video show you how to simulate a high fidelity CAD drawing of the MSRE in OpenMC (open source monte carlo). You can install everything you need in 15 minutes and run it on your own computer.     
    
https://github.com/openmsr/msre
  
https://www.onshape.com/en/products/free
  
https://en.wikipedia.org/wiki/Molten-...
  
https://github.com/openmsr/msr-archive
  
https://moltensalt.org/
  
https://github.com/openmc-dev/openmc
  
https://docs.openmc.org/en/stable/
