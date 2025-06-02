# Chapter 1

## Website Design Learning Session

Abi guided Ning through the process of setting up and using Jupyter Book, a tool for creating web pages, on a Mac. They discussed the installation of Python and Jupyter Notebook, as well as the use of terminal commands to create a book template. Abi explained that while Python knowledge is not required, tools like ChatGPT can assist in generating code.

## Jupyter Book Cloning and Building

Abi demonstrated how to clone and build a Jupyter Book project using GitHub and VS Code. He showed Ning how to create a repository, copy the book's contents, and build the HTML files locally. Abi emphasized the importance of using VS Code as a development environment and promised to send Ning detailed instructions via email (nah - via a temporary `github repo`).

```sh
git clone https://github.com/ukubona-llc/ning
```

## Git and GitHub Usage Tutorial

Abi demonstrated how to use Git and GitHub, including committing changes, writing commit messages, and pushing content to a repository. He encountered some access issues but resolved them by inviting himself as a collaborator on the company website. Abi explained that using multiple GitHub accounts on the same computer can be complex, and he chose to invite his personal account as a simpler solution.

```sh
git add .
git commit -m "debug display command"
git push
```

## Github Pages Website Deployment

Abi demonstrated how to set up and deploy a website using Github Pages, showing Ning the process of importing content, creating branches, and configuring settings. He explained how to work locally with a main branch while keeping the website content on a separate branch, and emphasized the importance of backing up work to Github rather than relying solely on local storage. Abimereki also showed how to update and modify the website content through the command line, using a demo title as an example.

## Jupyter Book Creation and Editing

Abi demonstrated how to create and edit a Jupyter Book, including changing chapter titles, updating the table of contents, and configuring the book's title, authors, and logo. He showed how to edit and build HTML locally before publishing to the internet, and explained that the book supports Python, Stata, and R code blocks. Abi encountered an issue running Stata code in the Jupyter environment, noting that additional setup would be needed to use Stata in the book.

## Jupyter Book Project Demonstration

Abi demonstrated how to update content, change logos, and add references in a Jupyter book project. He showed how to use Git and GitHub to track changes and push updates to a website. Abi explained the process of adding Python code and its output to the book, highlighting the collaborative and teaching potential of this tool.

## Visual Studio Code Setup Instructions

Abi provided instructions to Ning for setting up Visual Studio Code on a Mac. He mentioned using an internship portal to access a token for setup, but noted that this method could allow others to access Ning's GitHub if using a borrowed computer. Abi suggested a more complex, automated approach that allows for creating and destroying the setup as needed. He promised to send instructions for the onboarding process and an access token. Abimereki also advised Ning to reach out via WhatsApp or email if she encountered any issues during the setup.

![](./internship-portal.png)

Just add access token to make it work (ask me via whatsApp for token)

## Rheumatology Data Access Challenges

Abiand Ning discussed Ning's work in rheumatology and the challenges of accessing data through a slow remote desktop. Abimereki warned Ning about potential security issues with the first step of installing VS code and offered to send her a summary of their discussion. He advised Ning to practice creating and destroying books and emphasized the importance of setting up Python and a local environment for the internship.

## Xcode Installation Guide for Ning

Abi guided Ning through the process of installing and verifying Xcode, the Apple development environment, on their computer. He explained that the installation process can take 5 to 10 minutes and may appear unresponsive, but it is crucial for development. Abi provided a command for checking if Xcode is installed and advised Ning to start with Part A of the installation process, with Part B recommended for later.

## GitHub Code Collaboration Demo

Abi demonstrated how to use GitHub for sharing and collaborating on code, particularly for Stata and terminal files. He showed Ning how to create a new file, access raw URLs, and update code, explaining the benefits of using GitHub over email for code sharing. Abimereki also covered how to install software using GitHub, including VS Code and Jupyter Book, and offered to help Ning with any questions she might have.

```stata
do https://raw.githubusercontent.com/ukubona-llc/ning/refs/heads/main/demo.do
```