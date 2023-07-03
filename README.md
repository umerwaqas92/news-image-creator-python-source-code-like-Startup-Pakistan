# News Image Creator - Python Source Code

This repository contains the Python source code for a News Image Creator. It allows users to generate custom news images by adding text overlays to a background image.

## Example Output
![Output Image](output_image.jpg)

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/username/news-image-creator-python-source-code-like-Startup-Pakistan.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place your desired background image in the project directory. By default, the image file should be named `abuzar-xheikh-qK9-2vp8nBw-unsplash.jpg`.

4. Modify the code in `news_image_creator.py` to customize the text overlay settings, such as font, size, position, color, and the news content.

5. In the `news_image_creator.py` file, locate the following line of code:
   ```python
   source_image_path = "abuzar-xheikh-qK9-2vp8nBw-unsplash.jpg"
   ```

   Change the value of `source_image_path` to the filename of your custom background image.

6. Write the news content you want to display on the image. Keep the news content within a maximum of 115 characters, and mark important words with asterisks (`*`) to highlight them.

   Example news content: "Pakistan's tourism industry *thrives* with *breathtaking* landscapes and *rich* cultural heritage, attracting *global* visitors."

7. Run the script:
   ```bash
   python news_image_creator.py
   ```

8. The generated news image will be saved in the project directory.

## Contact

For any questions or inquiries, please feel free to contact us at um.waqas.khan@gmail.com.
