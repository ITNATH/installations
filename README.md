# installations

install react vite


shift+right click select power shell

npm create vite@latest

react-shadcn-js

npm install

cd react-shandcn-js

code // to enter vscode

npm run dev

ctrl + c to stop the application // type(for yes)

install tailwind 

npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p

create a file in vscode called tsconfig.json re-name the file to jsconfig.json

input the following in the json file.

{
  "compilerOptions": {
    // ...
    "baseUrl": ".",
    "paths": {
      "@/*": [
        "./src/*"
      ]
    }
    // ...
  }
}

input in vite.config.ts folder
resolve: {
    alias: {
      "@": path.resolve(__dirname, "./src"),
    },
  },

next install shadcn

npx shadcn-ui@latest init

click ok 

Would you like to use TypeScript (recommended)? ... no / 

 Which style would you like to use? » - Use arrow-keys. Return to submit.
>   Default

 Which color would you like to use as base color? » Slate

Where is your global CSS file? » src/index.css

click ok x6 on diff occassion to complete

install this next

npx shadcn-ui@latest add button 

when done: goto src folder import button into app.js 

import {Button} from "./components/ui/button"


function App() {
   
  return (
    <>
      <div className="px-20">
      <Button>Hello world</Button>
      </div>    
      </>
  )
}

export default App



