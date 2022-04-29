# lightnovel-git

NOTE: Make sure you have initialized your repo, and set your remote with name "origin" and branch "master" to track your own remote. Easiest way to ensure this is to fork this repo.

[Example of my lightnovel repo](https://github.com/AsianKoala/lightnovels)
 
## Updating a repository
1. Set amount of chunks in `git_folder_handler.py` to your desired number
2. Run `git_folder_handler.py`
3. The program will prompt you if you wish to stop. If not, it will continue chunking through your entire repository.

## Adding new light novels to an existing folder
1. Add light novels to the folder
2. Follow `Updating a repository`

## Adding new light novels without folder
1. Create a folder named ".queue" inside the repo.
2. Add any light novels to this .queue folder
3. Run `pdf_folder_maker.py`
4. This will create new folders associated with those light novels in the .queue folder.
5. Follow `Updating a repository` 
