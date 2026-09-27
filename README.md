# computer_vision
# https://deeplizard.com/resource/pavq7noze3
# https://deeplizard.com/resource/pavq7noze2
!pip install kaggle

# Create folder
!mkdir -p dogsvscats_dataset

# Download dataset
!kaggle datasets download -d princelv84/dogsvscats -p dogsvscats_dataset

# Unzip dataset
!unzip dogsvscats_dataset/dogsvscats.zip -d dogsvscats_dataset
