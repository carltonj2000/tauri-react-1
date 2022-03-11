# Tauri And React Example 1

The code in this repository is based on the
[Tauri & ReactJS - Creating Modern Desktop Apps](https://youtu.be/BbZmLXBDGnU)
video.

Install rust from the instruction on the Tauri site and
then create a react app as follows.

```bash
mkdir tauri-react-1
cd tauri-react-1
npx create-react-app .
npm install -D cross-env @tauri-apps/cli
npm install @tauri-apps/api
yarn tauri init
yarn tauri dev
yarn tauri build
# image from build in ./src-tauri/target/release/bundle/...
```
