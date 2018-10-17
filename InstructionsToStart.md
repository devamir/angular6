Install GIT and open the the GIT Bash now run following command:
1. Run 
npm install -g @angular/cli

2. Go to your directory and 

3. Go to the project directory and launch the server.
ng serve --open

The ng serve command launches the server, watches your files, and rebuilds the app as you make changes to those files.
Using the --open (or just -o) option will automatically open your browser on http://localhost:4200/.

4.The src folder
Your app lives in the src folder. All Angular components, templates, styles, images, and anything else your app needs go here. Any files outside of this folder are meant to support building your app.

src
	app
		app.component.css
		app.component.html
		app.component.spec.ts
		app.component.ts
		app.module.ts
	assets
		.gitkeep
	environments
		environment.prod.ts
		environment.ts
	browserslist
	favicon.ico
	index.html
	karma.conf.js
	main.ts
	polyfills.ts
	styles.css
	test.ts
	tsconfig.app.json
	tsconfig.spec.json
	tslint.json
	
	
5. To create any new component run following
	Create the heroes component
	ng generate component heroes

	This command will generate 4 files
	$ ng generate component heroes
	CREATE src/app/heroes/heroes.component.html (25 bytes)
	CREATE src/app/heroes/heroes.component.spec.ts (628 bytes)
	CREATE src/app/heroes/heroes.component.ts (269 bytes)
	CREATE src/app/heroes/heroes.component.css (0 bytes)

	And update the app.module.ts to contain this new component
	UPDATE src/app/app.module.ts (396 bytes)

6. Now in order to use this component call the component by its name in the app.component.html
like following 
<app-heroes></app-heroes>

7. Check the localhost for the changes 
http://localhost:4200/ You will notice some changes

For more info go to angular site and make the changes in the app by following the below tutorial
https://angular.io/tutorial/toh-pt1

