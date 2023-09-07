This small project is about learning to create a simple production pipeline.

I used a simple redux project I had done earlier. I changed implemented a very simple http server without database that replaced the json server the project originally used.

The project has a pipeline that runs couple of tests and checks code quality. If the commit message does not contain '#skip', the version number tag is updated. Then the project is built and reployed to render.
