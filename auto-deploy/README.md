Auto-Deploy (Runs on port 8005) - Link
	Github -> Service Hook -> Website
	Update the file (GitAutoDeploy.conf.json)

Change url and path
	Start the server by typing:
		- python GitAutoDeploy.py --daemon-mode
	GitHub Service Hook URL
		- http://www.domain.com:8005