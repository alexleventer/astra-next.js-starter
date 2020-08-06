# Next.js/Astra Starter
A sample Next.js, [DataStax Astra](https://astra.datastax.com/register) starter app.

Contributor: [Alex Leventer](https://github.com/alexleventer)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/alexleventer/astra-next.js-starter)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/git?s=https%3A%2F%2Fgithub.com%2Falexleventer%2Fastra-next.js-starter&env=ASTRA_DB_USERNAME,ASTRA_DB_PASSWORD,ASTRA_DB_ID,ASTRA_DB_REGION)

## 🚀 Getting Started Paths:
1. [Run the app locally](#running-on-your-local-machine)
2. [Run the app on Gitpod](#running-on-gitpod)
3. [Deploy the app to Vercel](#deploying-to-vercel)

### Running on your local machine
1. Create a [DataStax Astra account](https://astra.datastax.com/register) and free-tier Cassandra database:
![image](https://user-images.githubusercontent.com/3254549/89589429-76042380-d7fa-11ea-917a-9bb1b1f11203.png)

2. Click 'Use this template' at the top of the README:
![image](https://user-images.githubusercontent.com/3254549/89589520-9af89680-d7fa-11ea-9df2-38ded5884927.png)

3. Enter a repository name and click 'Create repository from template':
![image](https://user-images.githubusercontent.com/3254549/89589574-b794ce80-d7fa-11ea-9c0e-4c7168501441.png)

4. Clone the repository:
![image](https://user-images.githubusercontent.com/3254549/89589607-cb403500-d7fa-11ea-98a7-8cbf66f02639.png)


5. Install Node dependencies with [Yarn](https://yarnpkg.com/): `yarn install` (Alternatively, use npm: `npm install`)
6. Run the set up script: ` . ./gitpod-setup.sh`
7. Start your app by running: `yarn start`(If using npm: `npm start`)
8. You can view your app at  http://localhost:3000/:
![image](https://user-images.githubusercontent.com/3254549/89589853-6b965980-d7fb-11ea-80ff-62dfe4b31ddb.png)

### Running on Gitpod
1. Create a [DataStax Astra account](https://astra.datastax.com/register) and free-tier Cassandra database:
![image](https://user-images.githubusercontent.com/3254549/89589429-76042380-d7fa-11ea-917a-9bb1b1f11203.png)

2. Click the 'Open in Gitpod link':

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/alexleventer/astra-next.js-starter)

3. Wait for your Gitpod workspace to start:
![image](https://user-images.githubusercontent.com/3254549/89589934-a5676000-d7fb-11ea-9690-36b876bbdb86.png)

4. Set your Astra credentials in the Gitpod terminal at the bottom of the screen:
![image](https://user-images.githubusercontent.com/3254549/89589982-c3cd5b80-d7fb-11ea-945f-a2413c456bb3.png)

You can find your database id here:
![image](https://user-images.githubusercontent.com/3254549/88744238-a1508980-d0fb-11ea-83fc-6efc6b370780.png)
5. Click the 'Open browser' button in the bottom right of the screen:
![image](https://user-images.githubusercontent.com/3254549/89590054-e6f80b00-d7fb-11ea-8a26-de2a019db71f.png)

6. View your application:
![image](https://user-images.githubusercontent.com/3254549/89590110-ff682580-d7fb-11ea-8e3a-47e3b552fc19.png)

### Deploying to Vercel
1. Create a [DataStax Astra account](https://astra.datastax.com/register) and free-tier Cassandra database:
![image](https://user-images.githubusercontent.com/3254549/89589429-76042380-d7fa-11ea-917a-9bb1b1f11203.png)
2. Click the 'Deploy' button:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/git?s=https%3A%2F%2Fgithub.com%2Falexleventer%2Fastra-next.js-starter&env=ASTRA_DB_USERNAME,ASTRA_DB_PASSWORD,ASTRA_DB_ID,ASTRA_DB_REGION)

3. Click continue:
![image](https://user-images.githubusercontent.com/3254549/89590194-232b6b80-d7fc-11ea-8dba-076b1a791a3e.png)

4. Enter your Astra database details and click deploy:
![image](https://user-images.githubusercontent.com/3254549/89590278-553ccd80-d7fc-11ea-91b1-6d61c2aae20f.png)

5. Click visit to view your live app:
![image](https://user-images.githubusercontent.com/3254549/89590361-9208c480-d7fc-11ea-9692-92fc3e71b1ad.png)
