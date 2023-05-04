# Create a tailwind.config.js file

./tailwindcss init

# Start css tailwind watcher (JIT) in development

./tailwindcss -i input.css -o output.css --watch (or just run "npm run dev")

# Compile and minify your CSS tailwind for production

./tailwindcss -i input.css -o output.css --minify (or just run "npm run pro")

# Start a watcher for alpine js in development (It will also be complied for production )

./tailwindcss -i input.css -o output.css --watch (or just run "npm run build-js")

# Useful links

https://tailwindcss.com/blog/standalone-cli
https://www.youtube.com/watch?v=0jukD2yldTY

https://fontawesomeicons.com/svg/icons/laravel

https://www.youtube.com/watch?v=BR_9XquCegs&t=82s

### I always start my css like this, this might help someone.

'\*' {
margin: 0;
padding: 0;
box-sizing: border-box;
}

html {
background-color: #660066;
}

body {
min-height: 100vh;
border:5px dotted white;
width: 100%;

}
