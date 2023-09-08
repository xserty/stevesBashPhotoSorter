# stevesBashPhotoSorter

Organise/Import images and videos into a YEAR/MONTH/DAY folder structure based on the file's exif data.

The script has many features like:
- Generate a file containing all sorted images' CRCs (unique hash values associated with the file)
- Use the CRC file to check against sorted images (does not import new image if existing is already there)
- 'Resume' importing of images based on the CRC file it generates
- Keeps track of the CRC of sorted files and if the script comes across an image with same CRC but different exif date, it will check which file is older and sort the oldest file and removes newer file from the sorted image directory and CRC file
- Generate ~/.ExifTool_config file needed to run the script

Version 0.7 is my initial release to the public.
Any input/improvement is appreciated.

  WARNING: THIS SCRIPT IS VERY EXPERIMENTAL. USE WITH CARE.
Warning: always make a backup of all your pictures!
Warning: use this script at your own risk!
