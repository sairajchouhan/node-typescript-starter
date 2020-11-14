# node-typescript-starter
Get up and running with node and typescript

## To get started go through the following steps
**(1)** Clone the repo or download the zip file and open it your favourite editor

**(2)** Open a terminal in the root dicectory of the repo and run 
``` yarn  ``` or ``` npm install ``` this will install all the dependencies listed in your ```package.json``` in this case it will install three dev dependencies

**(3)** After installing the dev dependencies, run the script ```yarn watch``` or ```npm run watch``` this will tell the typescript to compile the file in ```src/index.ts```
it compiles every time the file changes

It looks like this after you run the watch script

![terminal](https://user-images.githubusercontent.com/57995897/99141731-3e680b80-2674-11eb-8440-ccf5bd66126c.png)

the compiled code goes into ```dist/index.js``` each time the file has some saved changes and the as well as you can change ```tsconfig.json``` file  accordingly as per your requirements and willingness (this is just my personal preference of tsconfig.json file)

**(4)** Now to run the actual code run ```yarn dev``` or  ``` npm run dev ``` and this will start nodemon at ```src/index.js``` 

It looks like this after you run the dev script

