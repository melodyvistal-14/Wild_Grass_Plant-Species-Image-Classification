# Wild_Grass_Plant-Species-Image-Classification

Step 1: Propose Plant Species

Spreadsheets: https://docs.google.com/spreadsheets/d/12T8bL8PXUJrgRlMW2doi9uiwOk98yH4tv2CZe0qb93g/edit?gid=0#gid=0

Step 2: Image Collection
Google Drive (Images and Vedio): https://drive.google.com/drive/folders/1HCWaoIXr3pMN7j1W0GnB3isuTlcl0tA0?usp=drive_link

Step 3: Upload Dataset to Teachable Machine
 Teachable Machine: https://teachablemachine.withgoogle.com/train/tiny_image
        images: https://drive.google.com/drive/folders/1f16mJ1cMPK4LXhrgwUpQSJFWuQaig08r?usp=drive_link
        
Step 4: Train the Model
       <img width="1479" height="765" alt="Screenshot 2026-02-14 060920" src="https://github.com/user-attachments/assets/2535f1be-7441-459c-854b-9e2577cb0adf" />
       <img width="813" height="686" alt="Screenshot 2026-02-14 061007" src="https://github.com/user-attachments/assets/c7f1402a-efea-453d-a5a5-87d527ec9b0b" />
       
Step 5: Collect “Under the Hood” Results
        <img width="952" height="852" alt="Screenshot 2026-02-14 061034" src="https://github.com/user-attachments/assets/f0810c30-8e88-45cb-bb51-3d2dcaf4c031" />
        <img width="930" height="720" alt="Screenshot 2026-02-14 061635" src="https://github.com/user-attachments/assets/45618817-8555-4cab-a693-1eeeb6dc1e8b" />
         
Step 6: Test the Model (Preview Section)
         https://drive.google.com/drive/folders/1w2jxLhJic0TtsrZzQcVP2JIiyRVwCSpT?usp=drive_link

Step 7: Export the Model
         https://drive.google.com/file/d/1fXtxP4l896wIjdan9Y1qnauFwxkEwQ1M/view?usp=drive_link

Answer the following questions based on your experience:

1. How did the number of images per class affect your model’s accuracy?
- The number of images per class did not affect the model’s accuracy because each class had the same number of images; the performance gap is likely due to overfitting rather than class imbalance.

2. Which plant species were most commonly misclassified and why?
 - Bermuda Grass, Carpet Grass, Goose Grass, Cyperus Grass, and Purple Nutsedge Grass were often misclassified because they look very similar in color, shape, and texture, making it hard for the model to tell them apart.

3. How did changing the epochs, batch size, or learning rate affect the training results?
 - With 50 epochs, training accuracy improved, but test accuracy stopped rising, showing overfitting. A batch size of 16 balanced learning speed and stability. A small learning rate of 0.001 helped loss decrease smoothly but slowed test accuracy improvement.

4. What challenges did you encounter during dataset collection and labeling?
 - The main challenges that i encounter is that, collecting a nice clear images, capturing different angles and lighting, labeling similar-looking species correctly, and removing poor-quality of images and capturing a 250 images of wild grass plants.

5. If you were to improve your model, what specific changes would you make and why?
 - To improve my model, I would get more clear images from plant databases and reliable websites, that showing different angles and lighting to help ,my model learn better.







