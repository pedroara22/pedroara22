```js
// Welcome to Pedro Araújo's Profile!

class FullStackDeveloper {
  constructor() {
    this.name = "Pedro Araújo";
    this.role = "Full Stack Developer";
    this.age = 19;
    this.languages = ["JavaScript", "React", "Node.js", "MongoDB"];
    this.hobbies = ["Coding", "Building", "Exploring new tech", "Learning"];
    this.location = "Brazil";
  }

  sayHi() {
    console.log(`Hello, I'm ${this.name}, a passionate ${this.role}!`);
    console.log(`Currently, I live and code from ${this.location}.`);
    console.log("Let's build the future together! 🚀");
  }

  checkSkills() {
    console.log("My Skill Set Includes:");
    this.languages.forEach(lang => console.log(`- ${lang}`));
  }

  showProjects() {
    console.log("Here are some cool projects I've worked on:");
    console.log("1. Weather Forecast App (React + API)");
    console.log("2. E-Commerce Website (Next.js, MongoDB, Node.js)");
  }

  ambitions() {
    console.log("Ambitions:");
    console.log("To create robust, scalable web applications that change the world.");
  }
}

const pedro = new FullStackDeveloper();
pedro.sayHi();
pedro.checkSkills();
pedro.showProjects();
pedro.ambitions();

