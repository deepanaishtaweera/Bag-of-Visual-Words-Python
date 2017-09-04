# Bag-of-Visual-Words-Python #

This is a python implementation of the Bag of Visual Words model. [Be sure to check it out on my blog](http://kushalvyas.github.io/BOV.html#BOV)

Project Architecture : 

	:::python 
	- root dir/
		|- images/
				|- test /
					|- obj1/
					|- obj2/

				|- train /
					|- obj1/
					|- obj2/

		|- helpers.py
		|- Bag.py 


	:~$ python Bag.py --train_set images/train/ --test_set images/test/



### Output

<center>
![im1](readme_im/ac1.png)
![im2](readme_im/bk1.png)
![im3](readme_im/bk2.png)
![im4](readme_im/dollar1.png)
![im5](readme_im/sbb3.png)
![im5](readme_im/normalized_7.png)
</center>



NOTE: I've added the MIT LICENSE to the repo. Anyone is free to use this code in accordance with the MIT LICENSE 
