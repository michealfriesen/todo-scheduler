# todo-scheduler
This app is meant to be an interface to interact with todo tasks, with the purpose of scheduling them into personal calendars.

### Getting Started:
To prepare the project for use, first follow [this guide](https://askfiqri.com/how-to-get-an-access-token-for-microsoft-graph-api-using-node-js-258723f29cc6) to create your own azure project, and replace the example.env with your own .env following the provided format.

Then, run `npm install` to download dependancies, followed by `npm start` to start the server.

By default, you should then be able to navigate to `localhost:3000` in a web browser to begin use.

### Current MVP Feature List:
- Parsing tasks
- Adding time estimate to tasks
- Scheduling tasks to a list of things available to do in a day.

### Nice to haves:
- I would like to have at minimum a server that polls/listens to updates, then updates the calendar / My Day page with a good number of tasks
- Calendar integration would be nice to allow for visualization on outlook or gmail
- CLI interface to add tasks would be nice