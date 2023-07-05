
# Assignment Tailwind CSS

Tailwind CSS is a highly popular and widely adopted utility-first CSS framework. It offers developers a streamlined approach to building responsive and customizable user interfaces. With its unique utility classes, Tailwind CSS allows for rapid development by providing a comprehensive set of pre-defined styles that can be easily applied to HTML elements.




## Features

- Created with HTML and Tailwind CSS
- Attractive
- Optimize file size
- 100% make with tailwind css



## Tech Stack

- HTML
- Tailwind CSS
- Node js


## Installation

Install of Tailwind CSS

```bash
  Step 1:- open Terminal and run (npx tailwindcss init).
```
```bash
  Step 2:- Add folder dist and under a folder a file #output.css and code file name ex-index.html
```
```bash
 step 3:- Add another folder src and under a folder a file #inputput.css
```
```bash
step 4:- Add codes in input.css file

@tailwind base;
@tailwind components;
@tailwind utilities;
```
```bash
step 5:- write .dist/*.html in config.js file

module.exports = {
  content: [".dist/*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
```bash
step 6:- All done jus run a code in terminal 

npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
```bash
step 7:- Add <link rel="stylesheet" href="output.css"> in html file
```

    
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/abhaysam2888?tab=repositories)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhay-verma-821699274)


