# EMNIST-Database
PLEASE READ!

An EMNIST database i created in CSV format (converted from a 28x28 pixel image)
Theres not too many examples for each number/character (165 for each) so would probably be best used as test input into your neural net.

The files are saved in the zip file as the file was too big to directly upload. I have included the python files which you can use to create your own csv files. I have also included the initial images before and after they were compressed and also the final csv file.

The 1st python file 'img_compress.py' turns the image (handwritten image of a alphabetical character) into a 28 x 28 pixel image to make it smaller and easier to be read by the next python porgram 'img2csv.py'.

The 2nd python file 'img2csv.py' takes all the images that are save in the attched zip file and turns them into a readable csv file, with each line representing a new image.

I struggled to find alphabetical characters dataset in csv format ready for input into a neural network so i thought id make my own using a few images of handwritten characters i found online. src = http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/

I will also add the python code in which i used to convert the images into 28x28 from their original size (alot bigger)
and i will also add the code to turn the images into a csv file

Each line in the CSV  is a seperate image, and the first character in each line represents the image that it is converted from.

Numbers are marked by their respective numbers (1=1,2=2,3=3, etc), each letter of the alphabet in capital letters is marked in capital (A,B,C,D,E,F etc) and lowercase letters are marked with a dash at the end (a-,b-,c-,d-, etc)
