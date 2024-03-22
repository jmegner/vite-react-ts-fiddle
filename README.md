# vite-react-ts-fiddle

## Steps I Did To Create This

In a terminal ...
- In this folder, I ran `npm create vite@latest .`.
  - You can also do `npm create vite@latest NEW_DIR_PATH` to create a dir.
  - Files already existed in this folder from cloning from GitHub, and I chose to proceed anyway.  This did wipe out the README.md file, but it does seem like you want to do the `npm create vite@latest YOUR_GIT_ROOT_FOLDER` because of root-liking files like `.gitignore`.
  - For framework, I selected `React`.
  - For variant, I selected `TypeScript + SWC`.
  - I could have ran `npm create vite@latest vite-react-ts-fiddle -- --template react-ts`, but that would have used Babel instead of SWC, and SWC is supposed to be much faster than Babel.
- The above command succeeded and gave the instruction to run basically `npm install && npm run dev`, so I did that.
  - The `npm run dev` runs the server at port 5173.  Pressing `q` and Enter quits the server.
