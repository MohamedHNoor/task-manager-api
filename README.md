# Task Manager API

> A robust API for managing tasks seamlessly. Built with Node.js, Express, and MongoDB.

## Built With

- JavaScript
- Node.js
- Express
- MongoDB

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

In order to run this project you need:

- Node.js installed on your machine
- MongoDB installed and running locally or accessible remotely

### Setup

Clone this repository to your desired folder:

```sh
  cd <folder>
  git clone https://github.com/MohamedHNoor/task-manager-api.git
```

### Install

Install dependencies with:

```sh
 npm install
```

### Usage

To run the project, execute the following command:

```sh
 npm start
```

### Configuration

Ensure MongoDB is running, and configure the connection URI in an environment variable named MONGO_URI. You can set it in a .env file or directly in your environment.

```sh
Example .env file:
  MONGO_URI=mongodb://localhost:27017/task-manager
```

### API Endpoints

- Create Task: POST `api/v1/tasks`
- Read Task: GET `api/v1/tasks/:id`
- Update Task: PATCH `api/v1/tasks/:id`
- Delete Task: DELETE `api/v1/tasks/:id`
- List Tasks: GET `api/v1/tasks`

## Authors

👤 **Mohamed Hassan Noor**

- GitHub: [@MohamedHNoor](https://github.com/MohamedHNoor)
- Twitter: [@MohamedHNoor](https://twitter.com/MohamedHNoor)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/mohamedhnoor/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/MohamedHNoor/task-manager-api/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to [@john-smilga](https://github.com/john-smilga) for his invaluable teachings in his Node.js course.
- Inspiration
- etc

## 📝 License

This project is [MIT](./LICENSE) licensed.
