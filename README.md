# Our Only Home WebApp

"Our Only Home" is a web application that was developed as part of the Administration process at CODE University of Applied Sciences in 2019 using MongoDB, Express, EJS and Node. This was my first coding project, and was completed within a time limit of one month.

The goal of the application is to empower individuals and organizations around the world to address the climate crisis by offering a platform for creating, comparing, and discussing actions to save our planet. The inspiration for the project came from the FridaysForFuture movement, which has gained significant attention and support in the past year for its efforts to limit global warming to 1.5°C.

I recognized the importance of this movement and its values, and wanted to find a way to support its efforts through the development of a digital tool. One of the key problems that I identified was the lack of concrete demands and actions within the movement, and I saw the potential for a database of climate actions to empower and support the FridaysForFuture movement in achieving its goals.

My approach was to focus on empowering individuals and groups rather than offering a specific solution, with the belief that a "hive mind" approach could be the most effective way to address the climate crisis. Overall, the "Our Only Home" web application is a unique and innovative approach to addressing the climate crisis, and offers a valuable resource for individuals and organizations looking to make a positive impact on the environment.

## Preview
<img width="996" alt="Screenshot 2022-12-20 at 16 31 28" src="https://user-images.githubusercontent.com/61158193/208721734-60c98e4a-519a-4fde-810b-6fec1709dfff.png">

<img width="992" alt="Screenshot 2022-12-20 at 17 51 12" src="https://user-images.githubusercontent.com/61158193/208721938-8296a357-ed3b-42b5-8270-118f2636c46b.png">

## Prerequisites
Before you begin, make sure that you have the following tools installed on your machine:

- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm) (comes with Node.js)
- [MongoDB](https://docs.mongodb.com/manual/installation/)

## Run Locally

Clone the project

```bash
  git clone https://github.com/RichardKruemmel/code-challenge.git
```

Go to the project directory

```bash
  cd code-challenge
```

Install dependencies

```bash
  npm install
```

Start the MongoDB daemon

```bash
  mongod
```

Start the server

```bash
  node app.js
```

The server will start and listen for incoming requests on port 3000 by default.
To access the server, open a web browser and navigate to http://localhost:3000.

There is some [dummy data](https://github.com/RichardKruemmel/code-challenge/blob/master/seeds.js#L5-L30) located inside seeds.js file. If you want to initialise the server with the dummy data uncomment [line 25 inside app.js](https://github.com/RichardKruemmel/code-challenge/blob/master/app.js#L25).

I hope this helps! Let me know if you have any questions or if you need further assistance.
