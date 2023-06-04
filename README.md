Our solution for the hackathon is a computer vision system designed to detect broken or worn teeth on excavator buckets. The goal of the system is to perform semantic segmentation of teeth on the bucket wheel excavator, accurately identifying the regions where the teeth are located.

To tackle this problem, we have developed a deep learning model using the concept of semantic segmentation. The model is trained on a dataset provided by Business & Technology Services LLP, which consists of 240 pairs of images and corresponding tooth masks. The images are in .jpg format, while the masks are in .png format.

The solution involves transforming the provided data using a code from the transform_solution.ipynb notebook. This transformation ensures that the data is properly preprocessed and ready for training and evaluation.

Once the data is transformed, our deep learning model is trained on the dataset to learn the complex patterns and features associated with broken or worn teeth. The model leverages state-of-the-art techniques in computer vision and deep learning, allowing it to effectively analyze the images and accurately segment the tooth regions.

After training, the model can be used to predict tooth segmentation on new images of excavator buckets. The system takes in an input image and processes it through the trained model, producing a segmentation map that highlights the regions where teeth are present. This information can be used for further analysis, such as identifying broken fragments of teeth, detecting metal fragments in goods, or preventing damage to the crushing device and excavator.

To submit the solution for evaluation, we provide the output in .csv format, which contains the segmented tooth regions for each input image. This format ensures compatibility and ease of evaluation by the organizers.

We would like to acknowledge Business & Technology Services LLP for providing the task data and descriptions, which allowed us to develop and showcase our solution for the hackathon.
