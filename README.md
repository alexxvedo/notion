Notion application for linux.

Requirements:

	Nodejs
	Npm

Steps for installation:

	git clone https://github.com/alexxvedo/notion.git
	cd notion/
	npm install --save-dev electron electron-builder
	npm run dist-linux
	cd dist
	sudo dpkh -i <notion.deb>

Done.

If you want to change the installation file type you can do that by changing it inside
the "build/targets" section of package.json

	"build": {
		"appId": "Notion",
		"linux": {
			"target": [
				"deb"
			],
			"category": "Utility"
	 	}
  	}

See al target here: https://www.electron.build/configuration/linux#LinuxConfiguration-target
