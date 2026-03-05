# Setup Instructions
Follow the steps below to install dependencies and run the Sign Language Translation project.

## 1. Install Python
Ensure Python 3.8 or higher is installed.

## 2. Clone the Repository
git clone https://github.com/your-username/sign-language-translation.git  
cd sign-language-translation

## 3. Install Required Dependencies
pip install -r requirements.txt

## 4. Download Dataset
Download the PHOENIX14 dataset and place the video files and annotation file in the project directory.
Example folder structure:
project/
│
├── src/
├── phoenix14t_videos/
├── phoenix14t.pami0.train.annotations_only.gzip

## 5. Run the Project
Execute the main Python script to start the translation system.
python src/main.py

## 6. Output
The system processes sign language videos and generates the translated text sentence.
