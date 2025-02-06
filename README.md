# content_machine
A windows python app that takes two videos and merges them together, creating and displaying captions for the first

## CLI USAGE
python {script name} --model_path {model} --video_path {video path} --audio_path {expected audio path (leave default for out of the box functionality)} --output_video_path {expected output path} --additional_video_path {bottom video path}

## Installation
Download the .zip file with the code. Extract it and move to the directory. Install the dependencies listed in the requirements.txt file by running pip install -r requirements.txt. Install whisper by following the steps on their website. When you run the file, a tkinter dialog will show up with options to choose directories and settings. When everything is set up, run the file and it will prompt you with success messageboxes as the processes are completed. For a more detailed overview, look at the terminal, where it will print more information. 

## Notes
In the last step of the process, I added batch functionality to reduce memory usage and preventing memoryerrors from occuring. If a memory error occurs, lower the batch size.
