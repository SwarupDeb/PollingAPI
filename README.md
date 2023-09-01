# Polling API 🗳️

Welcome to Polling System API, your go-to solution for creating, managing, and voting on polls effortlessly! 

## Project Overview 🚀

Here's a glimpse of what PollMaster API has to offer:

```
🌐 Create, manage, and delete questions and options.
🗳️ Cast votes for your favorite options.
🔥 Seamlessly powered by Node.js and MongoDB.
```

## Project Structure 📂

Here's the structure of our project:

```
📁 config
   └─ mongoose.js
📁 controller
   └─ home_controller.js
   └─ option_controller.js
   └─ question_controller.js
📁 controllers
   └─ option.js
   └─ question.js
📁 models
   └─ option.js
   └─ question.js
📁 node_modules
📁 routes
   └─ index.js
   └─ option.js
   └─ question.js
📄 .env
📄 .gitignore
📄 index.js
📄 package-lock.json
📄 package.json
```

## Getting Started 🏁

To get started with PollMaster API, follow these simple steps:

1. Clone this repository.
2. Configure your MongoDB connection in `config/mongoose.js`.
3. Install the required Node.js packages using `npm install`.
4. Start the server with `node index.js`.
5. Access the API at `http://localhost:YOUR_PORT`.

## Usage 📝

Here are some common API endpoints to get you started:

- Create a new question: `POST /questions/create`
- Add options to a question: `POST /questions/question ID/options/create`
- Vote for an option: `GET /options/:optionId/add_vote`
- Delete a question: `POST /questions/:questionId/delete`

Refer to our API documentation for detailed usage instructions.

## Contributing 🤝

We welcome contributions! Feel free to open issues and submit pull requests to help us improve PollMaster API.

Happy polling! 🗳️
