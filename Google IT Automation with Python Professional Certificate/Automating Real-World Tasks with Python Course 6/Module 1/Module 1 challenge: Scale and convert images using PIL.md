# Module 1 challenge: Scale and convert images using PIL


1. **You downloaded a compressed file named images.zip and want to access the images inside. How can you achieve this?**
   - **Answer:** Unzip the file using the following command: `unzip images.zip`.

2. **You're working on a Python script that needs to edit a photo. What functionality is not provided by the Pillow library?**
   - **Answer:** Editing individual pixels of the image.

3. **You just finished writing a Python script that automates a tedious task. To run the script directly from the command line, what do you need to do first?**
   - **Answer:** Use the `chmod +x <script_name>.py` command to grant executable permissions to the script.

4. **Imagine you created a script to resize all images in a folder to a standard size and store them in the /opt/icons directory. After running the script, which command would show you the names of the resized images?**
   - **Answer:** Use the `ls /opt/icons` command to list the contents of the directory.

5. **You're working on a Python program that opens an image file. After successfully opening the image, how can you retrieve information about its format?**
   - **Answer:** Use the `img.format` attribute on the image object.

6. **Imagine you found an image online but aren't sure about its size before using it in your web page. How can you write a quick Python script to confirm its dimensions?**
   - **Answer:** Here's a Python script snippet: 
     ```python
     from PIL import Image
     with Image.open("image.jpg") as img:
         print(img.format, img.size)
     ```
- **Answer:** Python cannot be used to analyze an image file without opening and processing it first.

7. **You're working on a Python project that needs to send data to another application. Which approach would likely leverage an API for data exchange?**
   - **Answer:** Utilize an existing library's functions designed for interacting with external APIs.

8. **Imagine you're working on a large video editing project that requires significant processing power. A distributed computing system could be beneficial because:**
   - **Answer:** It allows you to leverage the combined processing power of multiple computers to render the video faster.

9. **Imagine you're building a large-scale weather forecasting system that requires processing vast amounts of real-time data. Distributed computing offers an advantage because:**
   - **Answer:** It allows you to distribute the workload of data processing across multiple machines, enabling faster and more efficient analysis.

10. **You're working on a project that uses Docker containers, but over time, there's a build-up of old, unused Docker images cluttering your system. What's the recommended approach to remove them efficiently?**
   - **Answer:** Utilize the `docker image prune` command to target specifically unused images.
