===	Setup SSH ===

1.	ssh-keygen -t rsa -C "your_email@youremail.com"
2. 	copy from key.pub to github.com - account - ssh_keys
3. 	test: ssh -T git@github.com

===	Working with GitHub ===

1. Clone repo:
	git clone  git clone https://github.com/buuren/github_usage.git
	cd github_usage
	git init
2. Copy/Add files:
	git add README.md
	git add .
3.	Commit and push to master:
	git commit -m "adding readme..."
	git remote add github_usage https://github.com/buuren/github_usage.git
	git push -u github_usage master
	
===	Misc stuff ===

1.	Delete files:
	git commit -a -m "A file was deleted"