## Website Performance Optimization portfolio project

## Optimizing index.html
for optimizing the index to get the highest score, the following was made:
1. css and js were minified
2. css render-blocking was fixed
3. js was made async 
4. images were optimized
5. size of images was changed



## Optimizing pizza.html and main.js

1. changed selectorAll to getElement
2. Moved recuring functions and variables from the for loop to reduce the time
3. changed some of the calculations to make it faster

## How to run
To run the application you need first to clone it or download it from github.

After downloading you can setup a local server if you want to test the website on page speed as follows:

1. download and run localhost
``` bash
cd /path/to/your-project-folder 
python -m SimpleHTTPServer 8080
```

2. Download and run ngrok using the following
``` bash
cd /path/to/your-project-folder
./ngrok http 8080
```

After setting up the server, you need to run the index.html and to run the pizza page you need to click on Cam's Pizzeria or open it from the views/pizza.html