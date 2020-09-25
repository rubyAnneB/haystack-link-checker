# Haystack CLI Link Checker
Haystack is a command line tool that checks for broken links.
## Features 
- Coloured terminal text
- Exception handling for unkown links
- Support for UNIX and Windows style commands
## Getting Started 
Below are instructions for getting Haystack running on your machine. Let's find those needles!
### Prerequisites
You will need [Git](https://git-scm.com/) and [Python 3] to pull from this repository and run Haystack.
### Installation Using Git
First, go to the folder or workspace that you want to clone the repository into:
```bash
cd C:\myprojects
```
Where **myprojects** is where you want to place the repository. 
Next, issue the following commands:
```bash
# Clone this repository
git clone https://github.com/rjayroso/haystack-link-checker.git

# Go into the repository
cd haystack-link-checker

# Remove current origin repository
git remote remove origin 
```
### Installing Dependencies
 Be sure to upgrade to the latest version of Python as  pip is already installed if you are using Python 2 >=2.7.9 or Python 3 >=3.4.
```bash
# Install dependencies using pip 
pip install termcolor
pip install requests
```
### Running Haystack
```bash
# Once you have successfully installed Python and the dependencies, type haystack.py to see the help section
python haystack.py

# To see the version, use the argument -v or --version
python haystack.py -v

# To run haystack on your own HTML file
python haystack.py <filename>
```
## Author :book:
- [Royce Ayroso-Ong](https://github.com/rjayroso)
## License :page_facing_up:
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/rjayroso/react-vehicle-database-manager/blob/master/LICENSE) file for details.
## Acknowledgments :bulb:
I would like to thank my colleagues for reviewing my code and issuing suggestions for improvements.