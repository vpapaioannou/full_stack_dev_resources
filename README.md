A collection of resources for full stack development and Continuous Integration/Continuous Development. In case something is missing or a link is not working, please create an issue [here](https://github.com/vpapaioannou/full_stack_dev_resources/issues).

# Back-End - How to process data

- [API Design Guidelines](https://www.swift.org/documentation/api-design-guidelines/)
- [Django](https://www.djangoproject.com/)
  - Logging
    - [Logging in Django (answer by Yuseferi)](https://stackoverflow.com/questions/19875789/django-gives-bad-request-400-when-debug-false)
    - [Save Django logs in production](https://mattsegal.dev/file-logging-django.html)
    - [Manage logs w/ Nginx, Gunicorn and Django](https://mattsegal.dev/django-gunicorn-nginx-logging.html)
    - [Log aggregation w/ Papertrail](https://mattsegal.dev/django-logging-papertrail.html)
    - [Log requests and responses when run in production](https://scripting4ever.wordpress.com/2020/07/27/how-to-log-the-request-and-response-via-django-middleware/)
    - [django-request-logging module](https://pypi.org/project/django-request-logging/)
  - [AttributeError: 'NoneType' object has no attribute 'is_relation' during makemigrations (answer by Felipe Ferri)](https://stackoverflow.com/questions/43765732/how-to-trace-this-attributeerror-nonetype-object-has-no-attribute-is-relati)
  - [Customize Django Admin Page](https://realpython.com/customize-django-admin-python/)
  - [ViewSets w/o model](https://medium.com/django-rest-framework/django-rest-framework-viewset-when-you-don-t-have-a-model-335a0490ba6f)
  - Scheduling
    - [How to use python to schedule tasks in a Django application](https://stackoverflow.com/questions/62525295/how-to-use-python-to-schedule-tasks-in-a-django-application)
    - [Advanced Python Scheduler](https://apscheduler.readthedocs.io/en/stable/index.html)
    - [django-apscheduler](https://github.com/jcass77/django-apscheduler)
    - [Scheduling Example 1](https://github.com/CodeEnvironment/django-rest-framework-code/tree/master/weather)
    - [Scheduling Example 2](https://github.com/bobby-didcoding/did_django_schedule_jobs)
  - AppConfig
    - [AppConfig Troubleshooting 1](https://stackoverflow.com/questions/37429726/overriding-appconfig-ready)
    - [AppConfig Troubleshooting 2](https://stackoverflow.com/questions/59225246/how-to-use-django-appconfig-ready?noredirect=1&lq=1)

# Front-End - How to display data

- Angular
  - [Understand how Angular and similar frameworks work](https://hackernoon.com/the-mechanics-of-dom-updates-in-angular-3b2970d5c03d)
  - [Angular Core Blog](https://blog.angular-university.io/tag/angular-core/)
  - [Docs](https://angular.dev/overview)
  - [Tutorials](https://angular.dev/essentials/next-steps#tutorials)
  - [Reset form properly (answer by Abhinav)](https://stackoverflow.com/questions/48216330/angular-5-formgroup-reset-doesnt-reset-validators)
  - [Angular Material Icons](https://material.io/resources/icons/?style=baseline)
- CSS
  - [CSS colors w/ a name](http://bada55.io/)

# Automate CI/CD cycle

- [SSH](https://www.ssh.com/academy/ssh) Connect securely to a remote server.
- [SSH for Windows](https://www.putty.org/)
- [Bash script](https://www.geeksforgeeks.org/bash-scripting-introduction-to-bash-and-bash-scripting/) Automate repetetive workflows.
- [FileZilla](https://filezilla-project.org/index.php) Access files on a remote server similar to your local files.
- [SSH tunneling](https://linuxize.com/post/how-to-setup-ssh-tunneling/) Enables testing code localy developed on a remote server before deploying anything to production.
- [Remote display - X11](https://www.baeldung.com/linux/x11) Access a remote server from your local computer with a graphical user interface, alike to when logging to your own computer.


# Deployment - How to deploy your application

- [What is WSGI: Web Server Gateway Interface?](https://www.fullstackpython.com/wsgi-servers.html)
- [Gunicorn and Nginx in a nutshell](https://build.vsupalov.com/gunicorn-and-nginx/)
- [Nginx](https://nginx.org/en/)
- [Squid server](https://www.squid-cache.org/)
- [Nginx vs Squid](https://cloudinfrastructureservices.co.uk/differences-between-squid-proxy-vs-nginx/)
- [Gunicorn](https://gunicorn.org/)
- [Cythonize](https://cython.readthedocs.io/en/latest/src/tutorial/cython_tutorial.html)
  - [How to convert Python code to Cython (and speed up 100x)?](https://www.machinelearningplus.com/python/how-to-convert-python-code-to-cython-and-speed-up-100x/)
- [Docker](https://www.docker.com/)
  - [Commands Cheat Sheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf)
  - [Dockerfile cheat sheet](https://medium.com/@anjkeesari/dockerfile-cheat-sheet-1cb9e6eb1484)
  - [Optimizing Your Dockerfile](https://medium.com/@esotericmeans/optimizing-your-dockerfile-dc4b7b527756)
  - [All platforms Docker standalone .deb files. Useful for offline installation](https://download.docker.com/)
  - [Debug docker image I](http://www.openwebit.com/c/how-to-debug-docker-images/)
  - [Debug docker image II](https://medium.com/@betz.mark/ten-tips-for-debugging-docker-containers-cde4da841a1d)
  - [How to solve UnicodeDecodeError in Python 3.6? (answer by Daniel)](https://stackoverflow.com/questions/51026315/how-to-solve-unicodedecodeerror-in-python-3-6/51027262#51027262)
  - [Run Docker as non-root user I (non secure)](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user)
  - [Run Docker as non-root user II](https://docs.docker.com/engine/security/rootless/)
  - [Save and load Docker images as files (answer by Booba Skaya). Useful for offline Docker image import/export](https://serverfault.com/questions/701248/downloading-docker-image-for-transfer-to-non-internet-connected-machine/718470#718470)
  - [How to check if a process is running inside docker container?](https://stackoverflow.com/questions/23513045/how-to-check-if-a-process-is-running-inside-docker-container)
  - Linux Offline Docker installation
    - [Download .deb files](https://docs.docker.com/engine/install/ubuntu/#install-from-a-package)
    - [Download NVIDIA .deb files](https://gist.github.com/lamhoangtung/d19bb72a99639a762b6d935fbd080c7c)
    - [Uninstall any old version. Use purge instead of remove](https://docs.docker.com/engine/install/ubuntu/#uninstall-old-versions)
    - [Stop Docker socket before installing](https://github.com/moby/moby/issues/41792#issuecomment-750863884)
  - Performance
    - [Container isolation gone wrong](https://sysdig.com/blog/container-isolation-gone-wrong/)
    - [Monitoring greedy containers (Part 1)](https://sysdig.com/blog/monitoring-greedy-containers-part-1/)
    - [Another reason why your Docker containers may be slow](https://medium.com/hackernoon/another-reason-why-your-docker-containers-may-be-slow-d37207dec27f)
    - [Beating some performance into Docker for Mac](https://medium.com/homullus/beating-some-performance-into-docker-for-mac-f5d1e732032c)
    - [How to build Docker Images for Apple Silicon (aka M1 Chip)](https://jitsu.com/blog/multi-platform-docker-builds)
    - [Speed boost achievement unlocked on Docker Desktop 4.6 for Mac](https://www.docker.com/blog/speed-boost-achievement-unlocked-on-docker-desktop-4-6-for-mac/)
