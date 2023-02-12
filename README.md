# AI-Commit: The Commit Message Generator

💻 Tired of writing boring commit messages? Let AI-Commit help!

This package uses the power of OpenAI's GPT-3 model to understand your code changes and generate meaningful commit messages for you. Whether you're working on a solo project or collaborating with a team, AI-Commit makes it easy to keep your commit history organized and informative.

## How it Works
1. Install AI-Commit using `npm install -g ai-commit`
2. Generate an OpenAI API key [here](https://platform.openai.com/account/api-keys )
3. Set your `OPENAI_API_KEY` environment variable to your API key
1. Make your code changes and stage them with `git add .`
2. Type `ai-commit` in your terminal
3. AI-Commit will analyze your changes and generate a commit message
4. Approve the commit message and AI-Commit will create the commit for you ✅

## Options
`--list`: Select from a list of 5 generated messages (or regenerate the list)

`--force`: Automatically create a commit without being prompted to select a message (can't be used with `--list`)

`--apiKey`: Your OpenAI API key. It is not recommended to pass `apiKey` here, it is better to use `env` variable

## Contributing
We'd love for you to contribute to AI-Commit! Here's how:

1. Fork the repository
2. Clone your fork to your local machine
3. Create a new branch
4. Make your changes
5. Commit your changes and push to your fork
6. Create a pull request to the AI-Commit repository

## Roadmap

- [x] Support for multimple suggestions: Provide multiple suggestions for the commit message.
- [ ] Support for custom commit types: Allow users to specify a custom commit type manually.
- [ ] Automated scope detection: Detect the scope of changes and automatically include it in the commit message.
- [ ] Improved emoji suggestions: Enhance the emoji suggestions generated by AI-Commit to better match the changes made to the code.
- [ ] Commit message templating: Provide a customizable commit message template for users to follow.
- [ ] Interactive commit message generation: Allow users to interact with AI-Commit during the commit message generation process to provide more context and refine the generated message.
- [ ] Integration with Git hooks: Integrate AI-Commit with Git hooks so that it can automatically generate commit messages whenever changes are staged.
- [ ] Advanced diff analysis: Enhance AI-Commit's diff analysis capabilities to better understand the changes made to the code.
- [ ] Reverse commit message generation: Allow users to generate code changes from a commit message.

## License
AI-Commit is licensed under the MIT License.

## Happy coding 🚀
