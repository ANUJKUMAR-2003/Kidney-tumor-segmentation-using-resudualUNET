# Kidney-tumor-segmentation-using-resudualUNET
We have been given the scaned 3d images of kidney and masked images images. We have to build a deep learning model such that the trained model can easily classify the tumor part from the image.

# Download dataset
I have used the KITS19 dataset for this project. In this dataset the scans of 210 patients are already given.
Because of lack of resources i have used only 20 of them.
To download dataset run following commands..

`git clone https://github.com/neheller/kits19
cd kits19
pip3 install -r requirements.txt
python3 -m starter_code.get_imaging`

