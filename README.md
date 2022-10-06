Steps to setup project
======================
https://www.youtube.com/watch?v=4mOkFXyxfsU

npx create-next-app ecommerce-react

update the package.json with the following lines

"dependencies": {
    "@babel/core": "^7.17.9",
    "@sanity/client": "^3.2.0",
    "@sanity/image-url": "^1.0.1",
    "@stripe/stripe-js": "^1.25.0",
    "canvas-confetti": "^1.5.1",
    "next": "12.3.1",
    "next-sanity-image": "^3.2.1",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "react-hot-toast": "^2.2.0",
    "react-icons": "^4.3.1",
    "stripe": "^8.209.0"
  },

Now run the following command to update the package
npm i --legacy-peer-deps

Start the app using the following command
npm run dev

Sanity is a content management page
https://www.sanity.io/javascriptmastery2022

copy the lines and run it in our projects
npm install -g @sanity/cli
sanity init --coupon javascriptmastery2022

if you get the error when running the prior command, run the following command
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
and repeat the command sanity init ...


Adding into git
git config --global user.email "prem_udayan@yahoo.com"
git config --global user.name "Prem"
git remote -v
git remote add origin https://github.com/premudayan/ecommercereact.git


