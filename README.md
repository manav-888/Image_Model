# Gemini Image Model
![Screenshot 2024-06-02 at 12 55 33 PM](https://github.com/manav-888/Image_Model/assets/28830098/1230fb78-10b7-43dd-9500-8b49818c40e4)

# Building a Response from Image
![Screenshot 2024-06-02 at 12 56 16 PM](https://github.com/manav-888/Image_Model/assets/28830098/7dcccc9f-2213-495b-b4c2-d26a6b0548c4)


## Setup Instructions

Follow these steps to set up the project on your local machine:

1. **Clone the Repository:**
   ```
   git clone https://github.com/manav-888/Image_Model.git
   ```

2. **Create a Virtual Environment:**

   Note: We used Python 3.10.11 to create the virtual environment. Please ensure that you use the same Python version to avoid potential conflicts and ensure compatibility with the project dependencies.
   ```
   python3 -m venv venv
   ```

4. **Activate the Virtual Environment:**
   ```
   . venv/bin/activate
   ```

5. **Install Requirements:**
   ```
   pip install -r requirements.txt
   ```
    **  or: ** 

   ```
   pip install streamlit transformers google-generativeai python-dotenv torch torchvision torchaudio

   ```

6. ** Create .env  file   in same directory  and Configure GOOGLE API KEY  :**
   ```
    GOOGLE_API_KEY=" Insert Your KEY "
   
   ```

   **  or: ** 

   ** To run without Google API key  then hit submit query button with Hugging face model **

![Screenshot 2024-06-01 at 3 31 42 PM](https://github.com/manav-888/manav-wasserstoff-AiTask/assets/28830098/f8e9ddc0-8023-4bcd-9ada-3b7b34cea4bc)


8. **  Run a app.py file in terminal **
   ```
   streamlit run app.py
   
   ```
   ![Screenshot 2024-06-02 at 12 56 16 PM](https://github.com/manav-888/Image_Model/assets/28830098/202f799b-d346-4020-807c-83d258bbca67)

  
