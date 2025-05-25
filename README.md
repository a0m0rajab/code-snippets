Install Python on linux: 
- sudo apt update
- sudo apt upgrade
- sudo apt install python[version number]
- sudo apt install python3-pip
Using Venev
- sudo apt install python3-venv
- mkdir myproject
- cd myproject
- python3 -m venv myenv
- source myenv/bin/activate # This should be run from the same folder of your venev (which in this case it's myproject)
Deactive or remove
- deactivate
- rm -rf myenv

Other notes: 
- Pm2 is good for any script to keep it running on the server
- when you start hetzner, it start with their own OS, you need to install your own image later (do not forget). This cause issues like not being able to connect to server or having a connection failed issue.
