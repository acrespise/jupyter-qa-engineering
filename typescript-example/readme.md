# Javascript and Typescript Setup in Jupyter Lab

[tslab](https://github.com/yunabe/tslab) is an interactive JavaScript and TypeScript programming environment on Jupyter and Node.js that provides Javascript and Typescript kernal for Jupyter notebooks. Given that you already have jupyter lab installed, follow the installation directions at https://github.com/yunabe/tslab#installing-tslab to set things up including installing NodeJS. This [medium article](https://pguso.medium.com/setup-data-analysis-environment-with-typescript-949e22339268) also runs through the process. 

This typescript-example folder in a nodejs application with dependencies defined in the package.json. We assume you are familiar with how a nodejs application is organized. You will need to install of the application dependencies from the command line from within that folder.

    example:
    
      C:\Projects\notebooks\typescript-example> npm install  

 tslab should pick up the installed dependencies without trouble.

 Example Notebooks:

* api-example.ipynb - use the axios library to test an REST API call.
* import-ts-file.ipynb - example of loading external file into your notebook.
* mocha-test-runner-example.ipynb - programmatically run tests using Mocha from a notebook.
* mocha-simple-html-reporter-test-runner.ipynb - use mocha to create an html report linked to from the notebook.
* playwright-example.ipynb - use playwright to automate testing a website.
     