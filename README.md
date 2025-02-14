# Valentine's Day Special Webpage

This is a special Valentine's Day webpage designed to celebrate love and relationships. It features a lock screen with a password entry, a countdown timer, a gallery of memories, and a final heartfelt message. The webpage is interactive and includes animations, music, and a responsive design.

## Features

- **Lock Screen**: A password-protected lock screen where users can enter their anniversary date.
- **Countdown Timer**: Displays the time spent together in years, months, days, hours, minutes, and seconds.
- **Gallery**: A grid of images showcasing memories.
- **Final Message**: A heartfelt message that appears after viewing the gallery.
- **Interactive Elements**: Buttons, animations, and music to enhance the user experience.
- **Responsive Design**: The webpage is designed to work on various screen sizes, including mobile devices.

## How to Customize

### 1. Change the Password (Anniversary Date)
To change the password (which represents the anniversary date), follow these steps:

1. Open the `index.html` file in a text editor.
2. Locate the following line in the JavaScript section:
   ```javascript
   const correctPassword = "123456";
   ```
3. Replace `"123456"` with your desired 6-digit anniversary date. For example, if your anniversary date is February 14, 2025, you can use `"140225"`.
4. Save the file.

### 2. Change the Countdown Start Date
To change the start date for the countdown timer, follow these steps:

1. Open the `index.html` file in a text editor.
2. Locate the following line in the JavaScript section:
   ```javascript
   const startDate = new Date("2024-01-01T00:00:00").getTime();
   ```
3. Replace `"2024-01-01"` with your desired start date in the format `YYYY-MM-DD`. For example, if your anniversary date is February 14, 2025, you can use `"2025-02-14"`.
4. Save the file.

### 3. Change the Gallery Images
To change the images displayed in the gallery, follow these steps:

1. Open the `index.html` file in a text editor.
2. Locate the following array in the JavaScript section:
   ```javascript
   const images = [
       {url: 'https://i.ibb.co.com/VYs29z3q/630c280f1c5ac354c3ea9790f871afbf.jpg'},
       {url: 'https://i.ibb.co.com/Y4Sq52W1/illust-127031799-20250210-190202.jpg'},
       {url: 'https://i.ibb.co.com/VY7XL7R5/wp11581404-columbina-genshin-wallpapers.jpg'},
       {url: 'https://i.ibb.co.com/pvsCT8ND/FB-IMG-1739430005923.jpg'},
       {url: 'https://i.ibb.co.com/qYD2qZT2/FB-IMG-1739341348148.jpg'},
       {url: 'https://i.ibb.co.com/qFNDjSvk/FB-IMG-1738681281607.jpg'},
       {url: 'https://i.ibb.co.com/yrPtG5J/FB-IMG-1737997328251.jpg'},
       {url: 'https://i.ibb.co.com/MkgvPKQz/FB-IMG-1738573604325.jpg'},
       {url: 'https://i.ibb.co.com/C3wHmYM4/FB-IMG-1738595041385.jpg'},
       {url: 'https://i.ibb.co.com/gZ0Nmfzk/pixelcut-export.jpg'},
       {url: 'https://i.ibb.co.com/wFxwWPYw/491a56e0-d3eb-4a5b-841e-daaec70a7af0.jpg'},
       {url: 'https://i.ibb.co.com/9HQfRXv8/FB-IMG-1737778881764.jpg'},
       {url: 'https://i.ibb.co.com/rfKrSGzK/FB-IMG-1737858394430.jpg'},
   ];
   ```
3. Replace the URLs in the array with the URLs of your desired images. You can use image hosting services like [ImgBB](https://imgbb.com/) to upload your images and get URLs.
4. Save the file.

### 4. Change the Final Text Message
To change the final text message, follow these steps:

1. Open the `index.html` file in a text editor.
2. Locate the following section in the HTML:
   ```html
   <div class="final-message" id="finalMessage">
       <div class="heart-decoration">❤️</div>
       <div class="message-content">
           <h2>Untuk Cintaku Yang Terkasih,</h2>
           <p>
               Di hari Valentine yang istimewa ini, aku ingin mengungkapkan betapa
               berharganya dirimu bagiku. Setiap detik bersamamu adalah momen yang
               tak terlupakan, setiap senyummu adalah kebahagiaan yang tak
               ternilai.
           </p>
           <p>
               Perjalanan cinta kita mungkin belum sempurna, tapi justru
               ketidaksempurnaan itulah yang membuat kisah kita menjadi indah.
               Terima kasih telah menjadi bagian terindah dalam hidupku, untuk
               setiap tawa dan tangis yang kita bagi bersama.
           </p>
           <p>
               Aku berjanji akan selalu mencintaimu, menjagamu, dan bersamamu dalam
               setiap langkah kehidupan kita. Kamu adalah alasan di balik setiap
               senyumku, inspirasi di setiap langkahku, dan cinta yang mengisi
               setiap sudut hatiku.
           </p>
           <p>Happy Valentine's Day, My Love! ❤️</p>
           <p class="signature">Dengan Segenap Cinta,<br />Your Valentine</p>
       </div>
       <button class="nav-button" onclick="restartExperience()">
           Mulai Dari Awal ❤️
       </button>
   </div>
   ```
3. Modify the text inside the `<h2>`, `<p>`, and `<p class="signature">` tags to customize the message.
4. Save the file.

## How to Use

1. Clone or download the repository.
2. Open the `index.html` file in a web browser.
3. Enter the correct anniversary date (password) to unlock the content.
4. Enjoy the countdown timer, gallery, and final message.

## Credits

- **Creator**: [@xez0](https://github.com/xez0)
- **Music**: Add your own music file (`musik.mp3`) or replace the `musik.mp3` file in the same directory as the `v2.html` file.

## License

This project is open-source and available under the MIT License. Feel free to modify and use it for your own purposes.

---

Happy Valentine's Day! ❤️
