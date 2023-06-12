# Multilanguage comments structure

The main goal of this little project is to provide a usefull package of [snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_creating-your-own-snippets) for any type of developer. 
This package will save you a lot of time by providing you with many shortcuts for common types of comments that input default structure regarding what language you are using, provided you use VSCode for code editing.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Be sure to have [Visual studio code](https://code.visualstudio.com/download) installed.

### Downloading

If you just need to use the Snippets just clone the repository and be sure to checkout the `master` branch. Then you will find 2 files:
* A JSON file with all the Esker Snippets: Esker.code-snippets
* A BAT file to help you get the JSON into the right directory: UpdateCommentsStructureSnippetsIntoLocal.bat

Execute the BAT file by double clicking or from Bash by running:

```
./UpdateEskerSnippetsIntoLocal.bat
```
This will create/replace the MultilanguageCommentsStructure.code-snippets file in the right directory so that Visual Studio Code would be ready to use it.
Now you are ready to open any language file and type 'Start&end comment', 'Long comment' or 'Short comment' as keyword and start seeing all availabe Snippets.


