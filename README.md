## Setting up the project

# Installing the dependencies
First, install the frontend dependencies using the following command in the root folder:
```bash 
npm install 
#or
npm i
#or
yarn i
```
.

Then,preferrably open another instance of the terminal and navigate to the server folder of this directory, then run :
```bash
npm install
#or
npm i
#or
yarn i
```
again, to install all the server dependencies. This will include Express.js, Mongoose, JSON Web Tokens, Zod, Cookie Parser and their types. Make sure you have
nodemon installed as a global dependency, if not, you can run the following command:
```bash
npm i nodemon -g
```
# Running the Next.js Server
Now run the Next.js server using the following command : 
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
# Running the Backend Express.js Server
After running the front-end Next.js server run the Express.js backend server by navigating into the "server/dist/" directory and run : 
```bash
nodemon index.js
```

Open [http://localhost:3002](http://localhost:3002) with your browser to see the result.
