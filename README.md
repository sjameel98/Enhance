1. testGAN2.py has our training loop
2. model_test_2.py is our model
3. buildnewyalefaces.py and pngtonpy.py build our datasets (latter makes the npy file needed to run the training loop)
4. custom_results.py is used to create and evaluate results from our testing set, input a string for the picture of your choice
5. psnrgen.npy and psnrint.npy have psnr values of psnr for our psnrgen.npy
6. evaluating.py has a function used to calculates psnr for our interpolated and generated images
7. training_loss_g.npy and validation_loss_g.npy store our loss over the various epochs
8. resultsPSNR.py if run will evaluate PSNR on the generated images in the results file as well as produce bicubically interpolated images and calculate their PSNR
9. plot_values_epochs.py plots the PSNR and generator loss over time for the training and validation and bicubically interpolated images
10. visualize can take a random image from the results folder (input the epoch number) and create a visualization for it
