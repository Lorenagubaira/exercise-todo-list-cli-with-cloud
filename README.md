<!--hide-->
# Todo List CLI in Sync with the Cloud!
<!--endhide-->

<p align="center"><img src="https://github.com/breatheco-de/todo-list-cli-with-cloud/blob/master/preview.gif" width="500" /></p>

Today you will be building a TODO list using API's to sync it with the cloud.

You will practice:
1. Python lists/arrays.
2. Python Dictionaries.
3. Using the requests package for API communication.
4. HTTP Protocol.

We are going to be using [BreatheCode Todo's API](https://playground.4geeks.com/apis/fake/todos/) to upload and download the TODO's, please refer to the HTTP and REST lessons as a quick background research for the project.

- Get todo's by calling: `[GET] /todos/user/<username>`   
- Initilize the todo list: `[POST] /todos/user/<username>`  
- Update your todo list: `[PUT] /todos/user/<username>`  

<how-to-start>
  
## 🌱 How to start this project

Do not clone this repository because we are going to be using a different template.

We recommend opening the `python boilerplate`, using a provisioning tool like [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recommended) or [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternatively, you can [clone the GitHub repository](https://4geeks.com/how-to/github-clone-repository) on your local computer using the `git clone` command.

This is the repository you need to open or clone:

```sh
$ git clone https://github.com/4GeeksAcademy/flask-rest-hello
```

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

### Pasos

1. Install the dependent packages by typing: 

```sh
$ pipenv install --python 3
```

2. Get inside your virtual environment by typing: 

```sh
$ pipenv shell
```

3. You can run the project by typing: 

```sh
$ python src/app.py
```
4. You can also run the tests for the project: 

```sh
$ python src/test.py
```

</how-to-start>

## 📝 Instructions

- Your app must work from the command line [like this](https://github.com/breatheco-de/todo-list-cli-with-cloud/blob/master/preview.gif).
- The user should be able to add new tasks.
- The user can add as many tasks as they want.
- The user can delete tasks by specifying the task position in the list.
- The app must be able to save todo's to the cloud using [BreatheCode Todo's API](https://playground.4geeks.com/apis/fake/todos/)
- The app must be able to download (load) the todo's from the [BreatheCode Todo's API](https://playground.4geeks.com/apis/fake/todos/)


