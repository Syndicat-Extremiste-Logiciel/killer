# Killer App (Need to find a decent name)
Master project of Killer app.

# Project architecture

```
|
| - app : frontend submodule
| - srv : backend  submodule
|

```

# Install

To setup your development environment:
```
git clone https://github.com/Syndicat-Extremiste-Logiciel/killer.git
cd killer
git submodules init && git submodules update
```

Note: `git submodules` updates given a specific commit. In order to update to the latest `master`, you need to checkout master then pull changes.

E.g to update `app` submodules:

```
cd app
git checkout -B master
git pull
```

# Development

As a start, I suggest to use the **Github Flow**:

https://guides.github.com/introduction/flow/
