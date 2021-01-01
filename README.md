# Game Documentation

The repository only generates documentation for RPM games system scripts. This documentation is generated with jsdoc, so you first need to install it globally :

	sudo npm install -g jsdoc
	npm install @pixi/jsdoc-template --save-dev

## How to generate documentation

Assuming your repository is in the RPG-Paper-Maker's parent directory :

    chmod -u+rwx generate.sh
    ./generate.sh