# SEASON WIZ Framework

- SEASON WIZ is framework & IDE for web development.
- SEASON WIZ Support git flow

## Installation

```bash
pip install season
```

## Usage

- create project

```
cd <workspace>
wiz create myapp
cd myapp
wiz run
```

- `127.0.0.1:3000/wiz` on your web browser


## Roadmap

- plugin support
    - wiz based online plugin development env
    - support programmable api for plugins
- git flow
    - support management for remote branches

## Release Note

### 0.4.1

- WIZ API (js) changed (async mode)

### 0.4.0

- Integrate WIZ & Season Flask
- support git flow
- workspace structure changed
- base code workspace changed (mysql to filesystem)
- UI upgrade
- support installer

### 0.3.12

- framework on build

### 0.3.11

- socketio error display

### 0.3.10

- socket bug fixed

### 0.3.9

- command run modified (add pattern, ignores)

### 0.3.7

- change Framework Object

### 0.3.6

- Socket.io disconnect bug fixed

### 0.3.3

- Socket.io Namespace Injection

### 0.3.2

- Socket.io bug fixed

### 0.3.1

- Socket.io bug fixed


### 0.3.0

- add Socket.io 


### 0.2.14

- add response.template_from_string function

### 0.2.13

- add response.template function

### 0.2.12

- add variable expression change option

### 0.2.11

- interface loader update


### 0.2.10

- config onerror changed 

### 0.2.9

- add response.abort

### 0.2.8

- error handler in controller `__error__`

### 0.2.7

- response redirect update (relative module path)

### 0.2.6

- logger upgrade (file trace bug fixed)

### 0.2.5

- logger upgrade (log executed file trace)

### 0.2.4

- logger upgrade (code trace)

### 0.2.3

- error handler bug fixed

### 0.2.2

- apache wsgi bug fixed (public/app.py)

### 0.2.1

- apache wsgi bug fixed

### 0.2.0

- framework structure upgraded
- command line tool function changed
- submodule structure added
- logging 
- simplify public directory structure

