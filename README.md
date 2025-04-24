
## Setup
1. **Clone the Repository**:
   - Use GitHub Desktop to clone this repo, or download it as a ZIP from GitHub.
2. **Install Dependencies**:
   - Install Python 3.x.
   - Run `pip install -r requirements.txt` in a terminal, or manually install the libraries listed in `requirements.txt`.
3. **Download the Dataset**:
   - The datasize size is too large to upload, so i have provided the public link of google drive containing the dataset of Gurugram and california seperately and in the /data section, i have uploaded some of the same images just for references.
   - The dataset is too large for GitHub. Download it from https://drive.google.com/drive/folders/1zWbM4kLnmiKWS5BNSb-9HKHmEbaY26e_?usp=sharing for california dataset and https://drive.google.com/drive/folders/1EPZAisUa1mTHzlw4hHGU9uhVi9W9MxXm?usp=sharing for gurugram dataset.

## Usage
1. **Train the Model**:
   - Open `GAN_Training_California/Gurugram` and run it in your Python environment (e.g., VS Code, Jupyter Notebook, or Google Colab), please note that i have trained my model with the dataset stored in my google drive please update the links according to your environment.
2. **Generate Layouts**:
   - Outputs will be saved in the `outputs/` folder after training. (for some sample outputs)
   - Again, you can find all the ouptuts from public links: https://drive.google.com/drive/folders/1lxKUf5lZvBNFYvCfqTguD-2AyORkZb4k?usp=sharing and https://drive.google.com/drive/folders/18VLYigv4jZRC2USXeEWK84Ii98Cp-DfJ?usp=sharing
## Results
- Current outputs are noisy (see `outputs/`), lacking clear urban features.
- California dataset shows slight diversity compared to Gurugram due to structured layouts.

## Paper
- Find the published paper in `paper/IJMSRT25MAR040.pdf`.

## Authors
- Vandna, Rahul Raj Parida, Mayank Raj (School of Engineering and Technology, KR Mangalam University, Gurugram, Haryana)

## License
This project is submitted under the supervision of KR MANGALAM UNIVERSITY.
