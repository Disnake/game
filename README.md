# game
on:
  workflow_dispatch:
    inuts:
    name:
      description: "Disnake"
      required: true
      default: "Randel"
      
jobs:
  MyFavouriteJob:games
  runs on: ubuntu latest
  steps:
    -uses:actions/checkout@v2
    
    -name: Run a one line script
      run: echo,"Hello, $({github.event.input.name})!"
    
    -name: Run a multiline script
    run:
      echo Add other action to build,
      echo test, and deploy your project.
      
 TheOneThatDoesThings:
  runs on: ubuntu latest
    steps:
      -uses:
      -name:
        run: ls -a
      -name:Print contents of the Readme
        run: cat README.md    
