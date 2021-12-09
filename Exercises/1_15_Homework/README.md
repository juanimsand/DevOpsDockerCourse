# Link to project in docker hub

jimsand/fullstack-part1-anecdotes

# Running the image

Although a detailed README.md file could be found at the project docker repository. I will repeat the command to running the image here. This project image runs a react app on dev mode, and it must be running in an interactive terminal.

## Example

A possible command could be: docker run -it -p 3000:3000 jimsand/fullstack-part1-anecdotes

This will launch the react app on host port 3000 and you could access it by entering http://localhost:3000 on your browser.