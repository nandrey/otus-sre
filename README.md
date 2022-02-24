# otus-sre
This project is for study purpose only.

## Usage
After clone run "vagrant up" and you will get working development enviroment based on bento/ubuntu-18.04

Then "vagrant ssh" and run "python ./code/flask-sqlite3-todo-crud/app.py"

## Versions
Hypervisor - Oracle VM VirtualBox VM Runner v6.1.32

Vagrant - Vagrant 2.2.19

## Folders and Ports
Vagrant synced folder - ./code", "/home/vagrant/code

Code folder so new code may be placed there - ./code

Application is located in - ./code/flask-sqlite3-todo-crud/

Application is cloned from - https://github.com/renat-nizamov/flask-sqlite3-todo-crud

Application uses port 5000, forwarded to port 5000 on host

### Diagram
![Project diagram](https://github.com/nandrey/otus-sre/blob/master/diagrams/grouped_workers.png)
