# U-Net-CNN-for-binarization-of-Historical-Kannada-Handwritten-Palm-Leaf-Manuscripts
U-Net: Convolutional Neural Network for binarization of Historical Kannada Handwritten Palm Leaf Manuscripts

Setup and Install
git clone https://github.com/kaustubh-sadekar/LS-HDIB.git

cd LS-HDIB/

conda create -n py38 -c anaconda python=3.8

pip install -r requirements.txt


Run segmentation for your own image

python run.py cpu input_2.jpg unet_best_weights.pth

The output file will be saved as <INPUT_FILE_NAME>_output.jpg. For this specific example it will be input_2_output.jpg


For better understanding of the input arguments type python run.py -h

Reference: https://github.com/kaustubh-sadekar/LS-HDIB
