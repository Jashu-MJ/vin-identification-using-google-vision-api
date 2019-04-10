# vin-identification-using-google-vision-api


1)i have developed the model using google vision api 

2)the input for the program is the location of the folder with images(change the location in resize and in for loop of main() ) and api key(to be hardcoded in the code)

3)output of the program is the text read and the vin number of length 17 number only.(wont read if length is less than 17). the output is 
written into output.docx file

4)i have defined 2 functions like resize() to reduce the resolution of image from 4608 x 3456 to 640*480 and to decrease the size of the image because maximum siz e of the image that can be uploaded to vision api is 20 mb max and in one JSON request object size should not exceed 10 mb.
other function is divide_chunks() this will divide the the list of images into n size list where n to be hardcoded in the code.

5)In a request to Google vision API we can send maximum of 16 images and 'n' cant exceed 16

6)It could extract the text data and the output is written to docx and available in output.docx
