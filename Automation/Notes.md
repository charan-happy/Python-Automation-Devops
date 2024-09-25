# Activating Virtual Environment

- When working with python, it is good practice to create an isolated environment. This helps to detach from the os interpreter , environment & properly define the dependencies that will be used. Remember `explicit is always better than implicit`
This is especially Important in 2 scenarios :  
1. when dealing with multiple projects on the same computer, as  they can have different dependencies that can clash at some point. EX: Two versions of the same module cannot be installed in the same environment  
2. When working on a project that will be used on different computer. Ex: Developing some code on a personal laptop that will ultimately run in remote server.

- In python3, we can achieve this feature by using `venv` tool is installed as part of the standard library. 

## Getting Ready
- To create new virtual environment, do the following  
1. Go the main directory where project is created.
`$ cd my-project`  
2. Type `$ python3 -m venv .venv`, this will create subdirectory called `.venv` that contains the virtual environment.  
3. Before Activating the 
