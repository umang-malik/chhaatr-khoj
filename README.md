# Chhaatr Khoj

Chhaatr Khoj is a command line student search tool for IIT Kanpur students.

### Usage
  - Scrape the data using `./init`
  - Use `./ssearch [OPTIONS]` to search for the students

### Flags
  - `-r rollno`
  - `-n name`
  - `-p program`
  - `-d department`
  - `-h hostel`
  - `-u username`
  - `-g gender` (M/F)

Your can enter the substrings for the above parameters.  
Note: Enclose the input in `" "` if it contains spaces.

### Images
  - For this you need to have `feh` installed.
  - Install `feh` by running `sudo apt install feh`
  - Pass the `-i` flag in the arguments to get the images for the search results.
 
### Examples
```
$ ./ssearch -n umang -i
$ ./ssearch -d computer -h hall12
```