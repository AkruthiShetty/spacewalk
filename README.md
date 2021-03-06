# spacewalk

## Production Environment Installation
Install the current or LTS version of NodeJS.

Run the following commands:
```
npm install -g evachecklist
```

to execute the tool:

```
evac-checklist <options>
```

options:

| tag | description
| --- | ---
| -i, --input | input yaml path
| -o, --output | output html path
| -t, --template | optional html template to use for generating the output

other options:

| tag | description
| --- | ---
| -h, --help | help syntax
| -v, --version | tool version

## Dev Environment Installation
Install node LTS version.
Install Visual Studio Code
Clone repository 'https://github.com/jamesmontalvo3/spacewalk.git'
In visual studio code, open folder to view source code and other documentation in the repo.

After project is opened in VS Code, in the console, run npm install. This will install the js-yaml dependancy that is required to quickly parse the yaml files.

After npm install the package run node main.js. This should compile and run the javascript file main.js and log the parsed data in JSON format.
