Guide to installing Apps and Packages:
---
### This contains tips(commands) to install apps and packages:
Apps:
---

**Atom:**

	sudo snap install atom  --classic
	
**Chrome:**

	wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
  
	sudo apt install ./google-chrome-stable_current_amd64.deb

Packages:
---

**curl:**

	sudo apt install curl
	
**GIT:**

	sudo apt update && sudo apt install -y openssh-client git
	
**PIP:**

	curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
	python3 get-pip.py
	
**Virtualenv:**

	pip install virtualenv
