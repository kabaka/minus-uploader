# Minus Uploader

This simple script allows you to upload files to a folder on minus.com.

# Usage

    Usage: ./upload [options] files

    Options:
        -g, --gallery GALLERY            Gallery to which file should be uploaded
        -u, --username USERNAME          Minus user name
        -p, --password PASSWORD          Minus password
        -h, --help                       Show this message

## Example

    ./upload -u Kabaka -p 12345 -g screenshots scrot_1024x786.png
    
# To-do

* Refactor code.
* Stop asking for log-in credientials as command args (maybe?).
* Create nonexistent galleries.
  * Figure out how to rename galleries after creation since the bogus API docs
  are lying about `/api/SaveGallery`.
* Don't give direct image links for non-image files.
