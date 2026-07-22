# Rebuilding the Webpage with an AI Agent

Follow these simple steps to set up your project and let the AI agent build the webpage for you:

1. **Clone the repository**: Open VS Code, open a new terminal, and clone this repository to your local machine.
2. **Download original website files**:
   - Go to the website you want to rebuild in your browser.
   - Save the webpage as **"Webpage, Complete"** directly into the `temp` folder.
   - Use the **ImageEye** browser extension to download all images from the page, and save them in the `temp` folder as well.
3. **Run the AI Agent**:
   - Once all downloaded files are in the `temp` folder, tell your AI coding agent to execute the instructions in [temp/*PROMPT.md](file:///Users/timdaly/Desktop/prompts-repo/temp/%2APROMPT.md).
   - The agent will automatically organize and rename all files, create the correct folders, and write the layout and styling code into the empty [index.html](file:///Users/timdaly/Desktop/prompts-repo/index.html) and [styles.css](file:///Users/timdaly/Desktop/prompts-repo/styles.css) files.
