# jekyll-photo-gallery
Simple solution to display photos on Jekyll sites
I uploaded this layout because I couldn't find anything good when Googling.
# Usage
Step 1: 
  - Clone/ copy both photo_page.html and photoboard.md files
  - Place photo_page.html in your _layouts folder, photoboard.md in your working directory

Step 2:
  - Make new folder named images

Step 3:
  - Within images, make 5 subfolders named column1->5

Step 4:
  - Add photos to those 5 subfolders.
  - Images in each of those folders will make a column.

# Portability
This method requires no outside plugins; therefore, compatible with any Jekyll project.
You can also add your CSS easily.

# Demo
A live demo can be found here: https://sketchxxhouse.com/photoboard/

# Weaknesses 
  - Since the 5 columns are independently stored, there is a chance photos can be repeated without you knowing. Storing all the images in one place then randomly distributing them to the subfolders may be a good strategy. 
  - Currently, the template isn't mobile-friendly. Will fix in the future.
  - There are currently a few for loops through every photo on the site. Will try to combat in the future.
