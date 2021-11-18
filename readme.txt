Short code explanation:
1. Libraries are imported for proper usage in further code
2. Then we get a path to file folder and its subfolders by os.getcwd()
3. In for loop we make program list every subfolder that our code found in given path.
   	Also in the loop inside previous we make program analyze every picture inside subfolder,
	resize it to 128x128 pixels square and append it to our empty array that we defined earlier
4. Then we define the number of classes and we shuffle and split dataset
5. We set CNN model in Keras for training
6. We visualize on graphs Training Loss, Validation Loss and Training and Validation Accuracy
7. We make program predict to which class our images belongs to
8. We make another test on a different image
9. Visualizing output of CNN
10. Making cofusion matrix