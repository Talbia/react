### Creating Our First Expo Project!

Here in the terminal window, type

- `expo init DoneWithIt`
> That's the project name of the app we're going to build. 

Choose a workflow for building this app -
> We can use one of the `managed workflows or bare workflows`

```ssh
- Managed workflow: This takes care of all the complexity behind the scene. With a managed workflow we're not going to need those iOS or Android projects. We only have a pure JavaScript project.

- Bare workflow: In this, we're going to have a bare bone react native project, so we'll have those iOS and Android projects. 
```

For now, I'm using `blank managed workflow` to bring extra complexity. 

##### Your project is ready! 

In the terminal window, type

- `cd DoneWithIt` and `code .` to go to the project directory and open the code editor respectively. 

_Note: `DoneWithIt` is my expo project name_

- Select `New terminal` in VS code, type `npm start` allows to start the expo and opens a developer tool in the default browser named `Metro Bundler`.

_Note: Whenever Expo Developer Tool is disconnected from Expo CLI, use the `expo start` command to start the CLI again._

```ssh
Metro Bundler - it's the JavaScript bundler for react native as it is responsible for compiling all of our JavaScript files into a single file.
```



