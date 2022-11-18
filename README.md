NOTION DE ESCRITORIO PARA LINUX:

REQUISITOS: 

	Nodejs
	Npm

PASOS PARA INSTALAR:

	git clone https://github.com/alexxvedo/notion.git
	cd notion/
	npm install --save-dev electron electron-builder
	npm run builer-linux
	cd dist
	sudo dpkh -i <notion.deb>

Todo listo! 
