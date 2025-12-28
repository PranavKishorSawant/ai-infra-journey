Day-1 :Setup 

-created a SSH key "ssh-keygen -t ed25519"
-"cat ~/.ssh/id_ed25519.pub" to print the public key (not private key)
-created a repo "ai-infra-journey" with README.md , added .gitignore (and select Python) and MIT LICENSE
-pasted the public key to the github profile
-"ssh -T git@github.com" to verifies your laptop’s cryptographic identity using your private key. 
-created an ai-infra dir and cloned it to the github ai-infra-journey using "git clone git@github.com:YOUR_USERNAME/ai-infra-journey.git"
-created an nano day-1.md meaning a markdown file using nano 
-ctrl O for save 
-enter for confirm 
-ctrl X to exit 

 
-then created a python virtual env using "python3 -m venv venv" 
-activate venv using "source venv/bin/activate"  and "deactivate" to do so
-upgrade pip of the venv using "pip install --upgrade pip"
-"pip freeze > requirements.txt" to create a requirements file that writes the exact versions of all installed Python packages in the active venv.
-made hello.py and ran using "python hello.py"
