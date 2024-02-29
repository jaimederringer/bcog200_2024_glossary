# BCOG200 (2024) Collaborative Glossary README

This file contains the instructions for today's in-class activity.

**Objective:** To update a public repository on GitHub with a glossary for the BCOG200 course.

**Offer:** One bonus point for each person who successfully contributes a glossary entry during class time today (2/29/2024).

**Instructions:**
1. Go to the [GitHub website](https://github.com/) and create a free account if you don’t have one already. You will need a username, an email, and a password. 
2. Go to the repository page of the course glossary: [GitHub.com/jaimederringer/bcog200_2024_glossary](https://github.com/jaimederringer/bcog200_2024_glossary). Click on the Fork button at the top right corner. This will create a copy of the repository in your own account. 
3. Open your command line and navigate to the folder where you want to store the repository (most likely your bcog200/ folder). Type the following command to clone the repository from GitHub to your local drive: `git clone https://github.com/your-username/bcog200_2024_glossary.git`. Replace your-username with your actual GitHub username. [NOTE: If you have not previously worked with git, you may need to install it. For Windows, use the command: `winget install --id Git.Git -e --source winget` and then restart your terminal after it has installed.]
4. Open the folder bcog200_2024_glossary. You will see a file called glossary.md, which is a markdown file that contains the glossary entries. You can open it in any plain text editor, such as nano/pico/vim in the terminal or TextEdit (macOS) or Notepad (Windows). Each entry has the following format: - **Term**: Definition. For example: - **Neuron**: A specialized cell that can transmit electrical and chemical signals in the nervous system. 
5. Choose a term from the [course ebook](https://github.com/jonwillits/python_for_bcs/blob/master/ebook/book_contents.md) that is not already in the glossary. Write a clear and concise definition for it. Add your entry to the end of the glossary.md file, following the same format as the existing entries. Make sure your entry is unique and does not duplicate or contradict any other entry. Save the file when you are done. 
6. Go back to your command line and, from within the repository folder that you cloned and have been working in, type the following commands to update the repository on GitHub with your changes: `git add .`, `git commit -m "Added a new entry to the glossary”`, and `git push`. You can replace the message in quotation marks with your own description of the changes. 
7. Go to the repository page on GitHub and click on the Pull requests tab. Click on the New pull request button. This will create a request to merge your changes with the original repository. Add a title and a comment to explain your changes and click on the Create pull request button. 
8. Wait for the main branch owner (the instructor) to review and approve your pull request. Once your pull request is merged, your entry will be added to the glossary and visible to everyone. Congratulations, you have successfully updated a public repository on GitHub! 

Acknowledgments: This assignment text was initially drafted with Copilot (GPT 4.0) on 2/18/2024
