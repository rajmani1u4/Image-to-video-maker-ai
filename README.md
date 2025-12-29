# Image-to-video-maker-ai
This project uses OpenAI's DALL·E model to generate images based on a prompt, and then creates a video from those images. The video is generated and saved in .mp4 format.
1.Image-to-video-maker-ai This project uses OpenAI's DALL·E model to generate images based on a prompt, and then creates a video from those images. The video is generated and saved in .mp4 format.

2.Features Generate multiple images using OpenAI's DALL·E API. Create a video from the generated images. Save the video to your desired location. 3.Requirements Before running this project, ensure you have the following installed:

Python 3.9 or higher pip for installing Python packages 4.Required Python Libraries: openai: For accessing OpenAI's API to generate images. moviepy: To create a video from the generated images. Pillow: To handle image processing. tkinter: For the graphical user interface (GUI). requests: To download the generated images. You can install these dependencies using the following command:

pip install openai moviepy pillow requests

Setup i) git clone https://github.com/rajmani1u4/Image_to_Video_maker-ai. ii) cd your-repository iii) Set your OpenAI API key: https://platform.openai.com/account/api-keys In file Python File Insert API Key --- OPENAI_API_KEY = "your-api-key-here"

How to Run

Activate your virtual environment .\venv\Scripts\activate
Run the script: python image_to_video.py
