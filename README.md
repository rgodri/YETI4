# YETI4

## Decoding the transmission
The transmission file wouldn't open because every other byte was flipped, so all the information for the five images were contained in the transmission file, but could not open because the header pattern did not match the JPG structure. 

I switched every other byte in the code and read through the entire file which did in fact contain five images. I then separated each image by its header and created a file for each JPG. The fifth image contained a picture of a fox jumping over a sleeping dog, so I used the pangram "The quick brown fox jumped over the lazy dog" to decipher the symbols shown in the other images. The final message read "Congratulations on cracking the code. Your main YETI task is to create a code based tool that will be useful to members of the physics department. The tool can be a wesbite a script or anything so long as it incorporates coding. You will be judged on the usefulness and usability of the code and how much we are delighted. The quick brown fox jumped over the lazy dog."

I have attached the Jupyter Notebook which includes the code and step by step comments of how to decode the transmission.

## The project
The website is pretty straightfoward. The first page can give members of the physics department a quick look at upcoming department events as well as current parking conditions on campus. The second page allows members to take a little brain break and pet a cat (or not!). The third page provides a timer to make focusing on projects a little easier. 

## Final notes
Decoding the transmission was SO MUCH FUN! I felt like Ralphie in "A Christmas Story" when he was in the bathroom feverishly decoding Annie's secret message. 
