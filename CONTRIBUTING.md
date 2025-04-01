# Contributing Guide

We welcome contributions to our documentation project! Whether you're a seasoned writer or a first-time contributor, your help is valuable.

## How to Contribute

Here are several ways you can contribute:

* **Report Issues:** If you find errors, inconsistencies, or areas that need improvement, please [create an issue](https://github.com/jchirayil/indix-docs/issues/new) on our GitHub repository. Be sure to provide as much detail as possible, including the page URL and a clear description of the problem.
* **Suggest Enhancements:** If you have ideas for new topics, examples, or features, please submit an issue with your suggestions.
* **Submit Pull Requests:** If you're comfortable with Git and Markdown, you can submit changes directly by creating a pull request (PR).

## Contributing Workflow

1.  **Fork the Repository:** Start by forking the repository to your GitHub account.
2.  **Create a Branch:** Create a new branch for your changes. Use a descriptive branch name (e.g., `fix-typo-on-page-x`, `add-example-for-y`).
3.  **Make Changes:** Make your changes to the documentation files. All documentation is written in Markdown.
4.  **Test Your Changes:** If possible, build the documentation locally to preview your changes. See the [Local Development](#local-development) section for instructions.
5.  **Commit Your Changes:** Commit your changes with a clear and concise commit message.
6.  **Create a Pull Request:** Submit a pull request to the `main` branch of the original repository.
7.  **Review:** Your pull request will be reviewed by a maintainer. They may suggest changes or merge your PR.

## Writing Guidelines

* **Markdown:** All documentation is written in Markdown. See a [Markdown Guide](https://www.markdownguide.org/basic-syntax/) for syntax help.
* **Clarity and Conciseness:** Write in clear, concise, and easy-to-understand language. Avoid jargon where possible.
* **Consistency:** Follow the existing style and formatting conventions.
* **Examples:** Provide practical examples and use cases to illustrate concepts.
* **Images and Diagrams:** Use images and diagrams to enhance understanding. Place images in the `static/images` directory.
* **Links:** Use relative links for internal documentation pages.
* **Headers:** Use proper header levels (`#`, `##`, `###`, etc.) to structure the content.
* **Code Blocks**: Use code blocks with the correct language identifier.

## Local Development

To build and preview the documentation locally, follow these steps:

1.  **Install Hugo:** You'll need [Hugo](https://gohugo.io/getting-started/installing/) installed on your system.
2.  **Clone the Repository:** Clone the repository to your local machine:

    \`\`\`
    git clone https://github.com/jchirayil/indix-docs.git
    cd your-repo
    \`\`\`

3.  **Run Hugo Server:** Start the Hugo development server:

    \`\`\`
    hugo server

    \`\`\`

4.  **View in Browser:** Open your web browser and go to `http://localhost:1313` to view the documentation.

## Code of Conduct

This project adheres to the [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## License

By contributing to this project, you agree to license your contributions under the [License Name](LICENSE.md).