### StackGen Initialization repository for new StackGen projects

Here is a template maven project with the project structure required to install and run the StackGen library as a developer.

This project has the required dependencies in the pom.xml file, as well as a source Swagger/OpenAPI Schema file {COLETTE TODO: LINK TO DOCS} which will be used to create and launch a new StackGen app. The project also provides a simple launcher containing an example command line for generating the StackGen generated output project.

To get started:

```
git clone https://github.com/StarterInc/stackgen-init.git <your-project-name>
```

Once you have the repo downloaded, cd into the folder and go:

```
cd <your-project-name>
bash launcher.sh
```
After code generation completes, you can then view the newly generated project in the ```/gen``` folder:

```
cd gen
ls -ltr
```
