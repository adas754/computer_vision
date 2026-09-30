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
# !kaggle datasets download -d msambare/fer2013
# !mkdir -p mammals_dataset  # creates a folder to store the mammal dataset

# Download dataset
!kaggle datasets download -d asaniczka/mammals-image-classification-dataset-45-animals -p mammals_dataset  # downloads the mammal dataset

# Unzip dataset
!unzip mammals_dataset/mammals-image-classification-dataset-45-animals.zip -d mammals_dataset  # extracts the dataset
