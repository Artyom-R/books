Comic Library GitHub Upload Notes

Files in this package:
- index.html
- books.csv
- images/ (contains sample cover images)

How to use:
1. Upload all files and folders to the root of your GitHub repo.
2. If an old index.html exists, delete or overwrite it.
3. Open index.html and replace:
   const ownerEmail = "your-email@example.com";
   with your real email.
4. Edit books.csv in Excel when books change.
5. Save books.csv and upload the new file to GitHub.

CSV columns:
title,series,volume,status,notes,image,age,location

Image paths:
Use local paths like:
images/spiderman.jpg

You can replace the sample images with your own files while keeping the same file names,
or change the image paths in books.csv.
