# Getting Started

To clone this repo and setup a django container, run the following in
PowerShell (Docker Desktop) or Docker Quickstart Terminal
(Docker Toolbox). Remember `$` is the prompt, you do not need to type it. Also
you may want to `cd` to a directory where you want the repo to live (a class
directory for example). Docker Quickstart Terminal starts you in a directory
that you do not have write permissions in.

```console
$ git clone https://github.com/rxt1077/it310_django.git
Cloning into 'it310_django'...
remote: Enumerating objects: 39, done.
remote: Counting objects: 100% (39/39), done.
remote: Compressing objects: 100% (34/34), done.
remote: Total 39 (delta 2), reused 39 (delta 2), pack-reused 0
Unpacking objects: 100% (39/39), done.
$ cd it310_django
$ docker-compose up
Creating network "it310_django_default" with the default driver
Creating it310_django_web_1 ... done                                                                                  Attaching to it310_django_web_1
web_1  | Watching for file changes with StatReloader
web_1  | Performing system checks...
web_1  |
web_1  | System check identified no issues (0 silenced).
web_1  | January 25, 2020 - 11:55:48
web_1  | Django version 3.0.2, using settings 'it310.settings'
web_1  | Starting development server at http://0.0.0.0:8000/
web_1  | Quit the server with CONTROL-C.
```

Now open a web browser and go to [http://localhost:8000/welcome](http://localhost:8000/welcome)
(Docker Desktop) or [http://192.168.99.100:8000/welcome](http://192.168.99.100:8000/welcome)
(Docker Toolbox). When you are done you can type Ctrl-C in the terminal.
