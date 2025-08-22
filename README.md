# marimo-test

Very simple example of a Marimo app deployed to Github Pages.

For development purposes, edit an existing marimo app as: 

```bash
marimo edit test.py
```

All edits are performed in the browser as a development environment (just like Jupyter Notebooks), or test.py can be editted directly. For testing purposes, you can run the app locally on local host as: 

```bash
marimo run test.py
```

To export the app as a HTML page. use the WASM option to embed the necessary Python dependencies into the HTML page. This allows the app to run in the browser without requiring a server to run the Python code. 

```bash
marimo export html-wasm test.py -o test.html
```

To view the resulting static HTML page, you can open `test.html` in your web browser,  dynamic elements will only work if opend using a live server (eg VS code). 

Github Pages, the demo app si deployed at [https://kletts.github.io/marimo-test/test.html](https://kletts.github.io/marimo-test/test.html). 

On opening the page will download to the browser the necessary Python dependencies to run the app. 


