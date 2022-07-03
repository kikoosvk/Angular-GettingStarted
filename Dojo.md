## Install the Angular CLI

install node js
install vs code
install git

clone https://github.com/kikoosvk/Angular-GettingStarted

Go to package folder - APM-Start
open in vscode


package.json - list of packages

```
npm install
```

Start script in package.json
```
npm start
```

Cli builds the app, starts the webserver

http://localhost:4200/

Change the app.component file to see hot reload. (code recompiled, browser refreshed)

To stop the server: CTRL + C

Set Auto-save

ng serve - ng not recognized

install Angular cli globally

```
npm install -g @angular/cli
```

Create new angular project using the installed angular cli

```
ng new apm-new --prefix pm
```

# Component
add img

![[component.png]]

component = template + Class + Metadata 

app.component.ts

Naming convention: Feature + Component = AppComponent

class: properties and methods : CamelCase

MetaData
@Component annotation

selector

template

we need to import Component function from @angular/core

delete all app.component.ts and build app component from scratch