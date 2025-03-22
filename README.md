#CSS coding

/* Reset default margins and paddings */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;   
    /* for full screen  */
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f8f8f8;
}

.container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100vw;
    height: 100vh;
    padding: 50px;
}

.text-section {
    max-width: 50%;
    padding: 20px;
}

.text-section h1 {
    font-size: 48px;
}

.text-section .name {
    color: #333;
}

.text-section p {
    font-size: 20px;
    color: #666;
    line-height: 1.6;
}

.buttons {
    margin-top: 20px;
}

.btn {
    padding: 12px 24px;
    border: none;
    cursor: pointer;
    font-size: 18px;
    border-radius: 5px;
}

.learn-more {
    background-color: #333;
    color: white;
    margin-right: 10px;
}

.contact-me {
    background-color: white;
    border: 2px solid #333;
    color: #333;
}

.image-section {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
}

.image-section img {
    max-width: 500px;
    height: auto;
}


#HTML coding 

 <!DOCTYPE html>
 <html lang="en">
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Simpple UI</title>
     <link rel="stylesheet" href="style.css">

 </head>
 <body>
     <div class="container">
         <div class="text-section">
             <h1>I'm <span class="name">Syeda Ayesha Bukhari.</span></h1>
             <p>I am the student of <strong>Artificial Intelligence</strong> in Semester <strong>7th</strong> I am learning <strong>HTML & CSS</strong>.</p>
             <div class="buttons">
                 <button class="btn learn-more">Learn More</button>
                 <button class="btn contact-me">Contact Me</button>
             </div>
         </div>
         <div class="image-section">
             <img src="picc.png" alt="Developer Illustration">
         </div>
     </div>
 </body>
 </html>
 



