# York-Steganography-Dissertation

This project was about hiding information into 3-dimensional shapes in a process called 3D steganography.

There are many ways to do this but i based my version mainly off this paper:


Firstly the mesh is partitioned
![My Image](images/partition.png)

Then the information is embedded into each of these partitioned.
Information is embedded cryptographically by hiding it into the spacial properties of the object.
This causes minor deformations in the object which makes it differ from the original.
The aim is to cause the least amount of deformation and maximise the amount of data inputted into it.

![My Image](images/bunny.png)

Above you can see the original mesh and the watermarked mesh on the left.
On the right you can see the two models superimposed to show the slight deviations of the watermarked model's spacial gemoetry 
