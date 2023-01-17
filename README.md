</dl>
</div <div>
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg"
    width="80">
<h1>OpenAI Auto Markdown Docs</h1>
<hr>
<h3>Software and Packeges</h3>
<p>[description]</p>
<p><img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white" />
    <img src="https://img.shields.io/badge/Pytest-0A9EDC.svg?style=for-the-badge&logo=Pytest&logoColor=white" />
</p>
</div>
<hr>
<div>
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-github-open.svg"
        width="80" />
    <h2>Repository Structure</h2>
    <div>
        <h3>Modules (src)</3>
            <dl>
                <dt>processor.py</dt>
                <dd>This Python script contains functions to clone a codebase from a given URL, create a temporary
                    directory, and parse the codebase into a dictionary. The clone_codebase() function clones the
                    codebase from the given URL and stores it in the temporary directory created by the get_tmpdir()
                    function. The parse_codebase() function then reads the contents of each .py file in the codebase and
                    stores it in a dictionary with the file path as the key.</dd>
                <dl>
                    <dt>logger.py</dt>
                    <dd>This Python script sets up a logger with a ColoredFormatter, which allows for different log
                        levels to be printed in different colors. It also sets the log level to DEBUG.</dd>
                    <dl>
                        <dt>model.py</dt>
                        <dd>This script uses the OpenAI API to generate a summary of a Python script. It takes in a
                            dictionary of files and code as an argument and loops through each file and code. It then
                            creates a prompt for the OpenAI API to generate a summary of the code. The script then
                            stores the summary in a list and returns the list of summaries.</dd>
                        <dl>
                            <dt>builder.py</dt>
                            <dd>This script imports the pandas library and defines two strings containing HTML code. It
                                then defines a function called create_html() which reads a csv file and creates a string
                                of HTML code containing the data from the csv file. The function then returns the HTML
                                string which includes the two strings of HTML code defined earlier.</dd>
                            <dl>
                                <dt>main.py</dt>
                                <dd>This Python script uses the Hydra library to set up a configuration file for a
                                    code-to-language model. It uses the Pandas library to create a dataframe from the
                                    codebase, and the Markdownify library to convert the dataframe into HTML and
                                    Markdown documents. It then uses the Builder, Logger, and Model libraries to process
                                    the codebase, log the progress, and summarize the code. Finally, it writes the HTML
                                    and Markdown documents to the specified output directory.</dd>
                                <hr>
                                <div>
                                    <h3>Roadmap</3>
                                        <p>[description]</p>
                                </div>
                                <hr>