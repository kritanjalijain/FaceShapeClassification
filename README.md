# FaceShape 

Approaches to determine the face shape. (oval/rectangular/oblong/square/round/diamond/heart )


## Approach 1

### Using Dlib Landmarks

Procedure to run this program: 
1. locate the haarcascade file, dlib .dat file in the repository.
2. place the image file (face photo) in the same repository.
3. run the program


1. Line1 shows forehead length
2. Line2 shows face width
3. Line3 shows jawline length
4. Line4 shows face length

Based on the proportions of these lines face shape is calculated.
Even the angle of jaw is calculated. 

The accuracy of the result is highly subjective.

## Approach 2

### Using Resnet34 model and fastai

