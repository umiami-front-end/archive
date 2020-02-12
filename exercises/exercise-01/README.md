# Read Me

## Command Line

### Objectives

- Become comfortable with the command line
- Navigate among directories
- Move/copy/rename files
- Use wildcards


### Instructions

1. Open the Terminal application on your Mac. By default you will begin in your home folder.

2. Download the exercise files by clicking the "Clone or Download" button in this repository, then click "Download ZIP".

  This will download 20 blank text files. You will move all of these files into a directory structure you create via the command line.

  These files are named in a distinct way. Cats for adoption end in `-cat.txt`. Dogs for adoption end in `-dog.txt`. Food ends in `-food.txt`. Files without a special designation are pet accessories.

  *NOTE:* You may want to rename this folder `pet-store` and move it into your home folder.

  If you find yourself so off track that you must start fresh, delete your folder in the GUI and start fresh.

3. List only the cat breeds for adoption using a wildcard.

4. Create a `cats` directory.

5. Using a wildcard, move all the adoptable cats and cat food files into the `cats` directory. Move the cat accessories (`catnip.txt`, `litter.txt`, `toy-mouse.txt`) one by one into the `cats` directory. Ignore `ball.txt` for now.

6. Change to the `cats` directory. Create three new directories in `cats`: `accessories`, `food` and `for-adoption`. Move the files into their respective directories.

7. After files have been moved, rename all the files so they no longer have '-cat' in them. For instance, change `siamese-cat.txt` to `siamese.txt`; `dry-cat-food.txt` to `dry-food.txt`. (Ignore `catnip.txt` as this is a special case.)

8. Change from the `cats` directory to the `pet-store` directory. Are you in the correct place? Using the command which tells you your current directory.

9. If you are in the `pet-store` directory, list only the dog breeds for adoption using a wildcard.

10. From `pet-store`, create three new directory paths:

  `dogs/for-adoption`<br/>
  `dogs/accessories`<br/>
  `dogs/food`

11. Using these new paths, move the files into their respective categories from `pet-store`. For instance, move `pug-dog.txt` into `dogs/for-adoption`. Don't move the file into `dogs`, then into `for-adoption` -- do it all at once.

12. After files have been moved, rename all the files so they no longer have '-dog' in them. For instance, change `pug-dog.txt` to `pug.txt`; `dry-dog-food.txt` to `dry-food.txt`.

13. From here on, you will need to navigate the directories without my guidance.

  `ball.txt` could be used by either a cat or a dog. Make a copy of this file so one `ball.txt` files appears in `cats/accessories` and one appears in `dogs/accessories`.

14. Create two new files -- `cat-treats.txt` and `dog-treats.txt`. Place these in their respective `cats/food` and `dogs/food` directories. (You may either move to the directory and create the new files or create the new files somewhere in your directory structure and move them up/down the directory path. Maybe try both.)

15. In `cats/for-adoption` and `dogs/for-adoption`, add the name of the breed to each of these empty files. For instance, `american-shorthair.txt` should read "American Shorthair" when viewed. Try using command line redirection (*hint:* use `echo` to write  the string before appending). Try using different editors (i.e. `nano`, `emacs`, `vi`). Check your work by using `cat` (the command) or `less`.

16. Change the permissions of these files so only the user can read and write. Groups and others (all) should be able to read, but not write or execute the file(s).

17. Using the command line (only!), download the following images to their respective directories:

  - [cats](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/Cat_poster_1.jpg/640px-Cat_poster_1.jpg)
  - [dogs](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Collage_of_Nine_Dogs.jpg/546px-Collage_of_Nine_Dogs.jpg)

  Rename these files to be `cats.jpg` and `dogs.jpg`, respectively.

**Good Luck!**
