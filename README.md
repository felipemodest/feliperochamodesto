- 👋 Hey there, I’m Felipe Modesto
- 👀 I’m interested in HTML5, CSS3, JavaScript, Nodejs, Reactjs e React Native.
- 🌱 I’m currently learning HTML5, CSS3, JavaScript
 📫 How to reach me feliperochamod@gmail.com

<!---
feliperochamodesto/feliperochamodesto is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


const express = require('express')
const app = express()

const webDeveloper = {name:"Felipe", stack:"Full-Stack-Developer"}

app.get('/', (req, res) =>{
  return res.send(webDeveloper)
}),

app.listen(3000, () =>{
  console.log("Initing code...")
})

