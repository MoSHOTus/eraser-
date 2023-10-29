![](https://tech-writing-tools.s3.us-west-2.amazonaws.com/fd7b7fe1-2565-4845-eb66-3b0ca9587c99.png)

## AI Powered Markdown Editor

Supercharge yo## Table of contents

- [AI Powered Markdown Editor](#ai-powered-markdown-editor)
- [Features](#features)
  - [AI Assistant](#ai-assistant)
  - [Writing and Transformations](#writing-and-transformations)
  - [Maths](#maths)
  - [Code Snippets](#code-snippets)
  - [Media](#media)
  - [Sequence Diagrams](#sequence-diagrams)
  - [Import Options](#import-options)
  - [Export Options](#export-options)
  - [Publishing Options](#publishing-options)t content, code snippets and media!

## Features

### AI Assistant
- Generate the first draft of the article with AI
- Brainstorm ideas with AI
- Rewrite a sentence or paragraph using AI
- Generate and add code snippets using AI
- Add an explanation for the code snippets using AI
- Generate code snippet using AI and insert it in the article
- Get auto-suggestions to complete the sentence using AI
- Generate and insert images using AI

### Writing and Transformations
- Convert all section headings to titlecase with a single click
- Togggle to view detailed article metrics at the bottom of the editor
- Add Table of Contents
- Dictate and add content using speech recognition
- Find writing issues
  - Profanity issues
  - Inequality issues
  - Contractions issues
  - Passive voice
  - Redundant acronyms
  - Readability issues 
- Find all the links which don't contain a caption and automatically add the URL's page title as caption.
- Embed audio version of the article for your readers using text-to-speech.
- Maintain a todo list of article topics you want to write on using the **Article backlog** option!
- Add a signature text using settings to be automatically added at the end of every article

### Maths
Add Math expressions and formulas (ie. use Katex) in your article and MD Editor will render it beautifully. You can either add it inline, for example $\sqrt{3x-1}$ or add it as a block. For example, 

$$
\sqrt{3x-1}+(1+x)^2
$$

### Code Snippets

![](https://tech-writing-tools.s3.us-west-2.amazonaws.com/8b01d697-c562-4481-fdd8-43b6b0fc6c0e.png)


- With a single click, convert all code snippets in 
  - Github Gists
  - Pretty screenshots using [Carbon](https://carbon.now.sh/)
- Identify code snippet's language using browser run AI. It uses the same library as VS code for identifying the code's language.
- Prettify all code snippets with a single click

### Media

- Import images or CSV from a local file or a remote URL
- Add beautiful images with caption from [Unsplash](https://unsplash.com)
- Generate images using AI

### Sequence Diagrams

Add diagrams or charts in your article using [Mermaid.js](https://mermaid.js.org/). Simply add a code block of type `mermaid` to render the diagram. For example you can add a sequence diagram in your article with this code snippet.

![](https://tech-writing-tools.s3.us-west-2.amazonaws.com/f137138e-57db-4c1b-acd8-2019943e7909.png)

### Import Options

- Import a HTML or Markdown file and start editing it in Markdown.
- Convert Jupyter Notebook (IPYNB) to Markdown by simply importing a `.ipynb` file and continue editing it in Markdown.

### Export Options

- MD Editor supports multiple export options including:
  - Markdown file
  - Plain HTML
  - Styled HTML
  - PDF
  - DocX
  - Zip - It is a special export option where we download and bundle all remote images locally in a subfolder and update the Markdown file to reference the local path.
 
### Publishing Options

- **Medium:** Publishes the article as a draft to the connected Medium account.
- **Github Gist:** Creates a public Github Gist to the connected Github account.
- **Github Repo:** Lets you choose and browse a Github repo to directly publish the article to it.