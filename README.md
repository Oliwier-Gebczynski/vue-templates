
# Project Setup Instructions

## Install npm on Ubuntu:

1. Open the terminal.
2. Update the `apt` package list:
   ```bash
   sudo apt update
```
3. Install `npm`:
```bash
sudo apt install npm
```
4. Check the installed npm version (should be `>= 20.10.0`):
```bash
npm -v
```


## Install npm on Windows:
1. Download and install the latest version of `Node.js` from the official website: [Node.js](https://nodejs.org/).
2. After installation, `npm` will be installed automatically.
3. Check the installed npm version (should be `>= 20.10.0`):
```bash
npm -v
```

## Create a Vue.js project:

1. Install `Vue CLI` globally (if not installed):
```bash
npm install -g @vue/cli
```

2. Create a new Vue project:
```bash
vue create project-name
```

3. Navigate to the project folder:
```bash
cd project-name
```

4. Run the project in development mode:
```bash
npm run serve
```
This will start the development server. Open your browser and go to `http://localhost:8080/` (or another port if 8080 is occupied) to see your Vue application.

5. If you want to build the project for deployment, use:
```bash
npm run build
```
The output files will be available in the `dist` directory.

Now you have npm installed, a Vue.js project created, and it running in development mode. You can start writing code in the Vue source files in the project folder.

