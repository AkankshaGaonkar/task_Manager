# taskMaster
Task Master is a To-Do list Web Application built using python programming language in a python virtualenv .This virtualenv is used to manage Python packages for different projects. Using virtualenv allows you to avoid installing Python packages globally which could break system tools or also work with other people and diffrent other projects. Backend is designed by flask micro web framework and sqlalchemy as database and front end is designed by HTML5 & CSS3.It tabulates and display all unfinished and finished tasks. We can add new task, delete and update unfinished task.


### How To Run
1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv env
```

3. Then run the command:
```
$ .\env\Scripts\activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```
<img height=400 width=900 src="https://github.com/AkankshaGaonkar/task_Manager/blob/main/Screenshot%20(349).png" />
