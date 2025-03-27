 Step 1: Install Required Libraries

This installs two tools:
- openai: lets you connect to OpenAI's image generator
- requests: lets you download files (like images) from the internet
  
![Screen Shot 2025-03-27 at 5 12 44 AM](https://github.com/user-attachments/assets/6ac6c2e9-df9f-4653-a33e-bb512fb9bbb5)

Step 2: Set Up OpenAI Client
- This connects your code to OpenAI using your secret API key
- This is how OpenAI knows it's you and lets you use their image tools
  
![Screen Shot 2025-03-27 at 5 13 29 AM](https://github.com/user-attachments/assets/bb7ae7f5-ae88-4ae0-b7cd-1685a75044c0)

Step 3: Create a Safe File Name
- Turns your input (like a sentence) into a filename
- Example: "Golden Temple View" becomes "golden_temple_view.png"
- This keeps filenames clean and easy to save

![Screen Shot 2025-03-27 at 5 16 28 AM](https://github.com/user-attachments/assets/a69bc3b4-0bea-45c6-8a43-8705d04145a0) 

Step 4: Download the Image 
- Downloads the image from the internet using the URL
- Saves it as a .png file on your computer
- Tells you if it worked or failed
  
![Screen Shot 2025-03-27 at 5 17 19 AM](https://github.com/user-attachments/assets/f09ba886-ac46-4dcf-920a-d6fa603eec88)

Step 5: Generate the Image with OpenAI 
- Sends your prompt (like "a Punjabi thali") to OpenAI
- OpenAI creates an image and gives you a link
- You download that image and save it using the filename function
  
![Screen Shot 2025-03-27 at 5 18 52 AM](https://github.com/user-attachments/assets/40ded814-8d02-472c-82ec-35b15c001fbb)

Step 6: Use the Function with a Prompt
- You give the program a sentence (the prompt)
- The program generates and downloads an image based on that prompt
  
![Screen Shot 2025-03-27 at 5 19 07 AM](https://github.com/user-attachments/assets/dda0f5d2-641c-4196-947d-ce39fd4b0914)

 Step 7: Show the Image
 - Finds the image file using the same filename as before
- Shows the image inside your notebook
  
![Screen Shot 2025-03-27 at 5 19 55 AM](https://github.com/user-attachments/assets/993dc610-2759-447f-9f7d-bb3f4fd1e93e)

Step 8: All-in-One Function (Optional)
- Combines everything (generate + download + show) into one step
- You just write one line, and the whole process runs

![Screen Shot 2025-03-27 at 5 20 11 AM](https://github.com/user-attachments/assets/bcc35fd6-a4c1-45a3-9091-ff3395775e79)
