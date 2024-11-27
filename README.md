<h1 align="center">Omotosho Joseph</h1>

<h2 align="center">About me</h2>

```ts
import SoftwareDeveloper, { IBioDetails } from 'omotoshojoseph';

export default class Bio extends SoftwareDeveloper {
  name     = 'Omotosho Joseph';
  location = 'Lagos, Nigeria';
  
  getDetails(): IBioDetails {
    return {
      "- ⚡ Quick bio:":                    "Quality oriented self motivating engineer that is product and business oriented, evolving and enthusiastic about building stuff",
      "- 👯 I’m looking to collaborate on": "Node, Typescript, React, AWS and Docker related projects",
      "- 💬 Ask me about":                  "Node, React, Typescript, MongoDB, Software Design & Architecture, Web-Dev and CI/CD Pipelines",
      "- 📫 How to reach me:":              "joseph.omotosho98@gmail.com",
    };
  }
}
```

