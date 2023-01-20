# AI-IMAGE-GENERATOR
In this project, I have used OpenAI and the DALL-E model to create a web app that will generate images from scratch based on the entered text.


This is a simple image generator built with Node.js and Express that uses OpenAI's Dall-E models to generate images.

![image](https://user-images.githubusercontent.com/42038161/213789832-66c1ba23-dc13-4a43-a829-6bff5f7a22db.png)


## Usage

Rename the `example.env` file to `.env`.

Generate an API KEY at [OpenAI](https://beta.openai.com/) and add it to the `.env` file.

Install the dependencies

```bash
npm install
```

Run server

```bash
npm start
```

Visit `http://localhost:5000` in your browser.

The endpoint is at `POST http://localhost:5000/openai/generateimage`.
