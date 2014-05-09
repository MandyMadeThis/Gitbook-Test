#GitBook Style Guide Test

Here is what I've learned about the GitBook Process …

* The Summery file is what controls the hierarchy of the whole book.
* You **Cannot** change the name of the summery. If you do, the rest of the code will not work.
* The sections of the book are defined here in the summery file in list format. Do not put any spaces between the lists - this causes a bug and the local server will fail. If it does not appear in this summery file, it will not be on the site.
* Every markdown file sound be inside a folder in the root of the repo. This will get compiled into html pages inside of folders that will be placed inside of the _book folder in the same repo.
* The first file in each category must be named README.md - this is case sensitive (as is the README and SUMMERY file in the base of the project, if they are named anything else, the book will not work)
