#### Why?

I wanted something more barebones than the official CRA + Electron boilerplate(which is really awesome) for throwing together a desktop app faster. This is based on (this amazing article) by @kitze[https://medium.com/@kitze/%EF%B8%8F-from-react-to-an-electron-app-ready-for-production-a0468ecb1da3] with some updates as electron has been improved since.

#### Scripts

These are the only two you need to worry about:

`npm run dev`

`npm run dist`

for the flag options to pass to dist check out the (electron docs)[https://www.electron.build/cli]. You might have to run it manually `npx electron-builder -wml` (notice the 'x' in 'npx') if you pass flags to the dist command.
