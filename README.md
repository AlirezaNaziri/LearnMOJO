# LearnMOJO
A repo for learning MOJO based on Codespaces DevContainer that provides an isolated and ready-to-use environment for running MOJO codes.

## How to deploy a vscode with Mojo and Jupyter notebook with Mojo
add codespaces if you have .devcontainer with devcontainer.json, docker-compose.yml and Dockerfile

in vscode, go to PORTS in terminal, right click and see forwarded address in open new window in browser. 

```
mojo HelloWorld.mojo
```

to build:
```
mojo build HelloWorld.mojo
```
then
```
./HelloWorld
```
