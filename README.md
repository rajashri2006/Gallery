# Ex.08 Design of Interactive Image Gallery
# Date:16-11-2024
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
         .gallery
        {
        background: linear-gradient(rgba(14, 22, 17, 0.605),rgba(30, 33, 30, 0.7)),url(Mc8kW4x9Q3aRR3RkP5Im_IMG_4417.jpg);
        background-size: cover  ;
        background-position: center;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        position: relative;
        }
        
        
         *{
            margin: 0;
            padding: 0;
        }
        .preview {
    width: 150px;
    border: 3px solid transparent;
    transition: border-color 0.3s, transform 0.3s;
    cursor: pointer;
    border-radius: 4px;
      }

.preview:hover {
    border-color: #dce5ee;
    transform: scale(1.05);
}

        

      .gallery img 
       {
        min-width: 0;
        flex: 1 1 10px;
        object-fit: cover;
        
        transition: 0.5s;
       }
       .gallery img:hover 
       {
        flex: 1 1 280px;
        
       }
    </style>
</head>
<body>
    
      <div class="gallery">
        <img class="preview" src="download.jpeg"/>
        <img class="preview" src="images (4).jpeg"/>
        <img class="preview" src="images (1).jpeg"/>
        <img class="preview" src="images (2).jpeg"/>
        <img class="preview" src="images (5).jpeg"/>
      </div>
    
</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-13 222909](https://github.com/user-attachments/assets/13c13893-ea8c-4422-ac25-265e03f8089f)

![gal1](https://github.com/user-attachments/assets/81174888-2719-4836-bc51-8179a415f0c0)

![cat1](https://github.com/user-attachments/assets/a65eaee8-8b29-4416-b3bb-62687c19f0ef)

![gal2](https://github.com/user-attachments/assets/f514be2f-9156-4b84-b441-1889a4c6361d)

![cat2](https://github.com/user-attachments/assets/25e44f16-290b-4dcf-9b7c-f02c7330ee34)

![gal3](https://github.com/user-attachments/assets/d2f2ee0e-eccf-4619-bb06-a5fd61bda73a)

![cat3](https://github.com/user-attachments/assets/368744f4-c3c5-4049-ae6d-272a99d63705)

![gal4](https://github.com/user-attachments/assets/00ae3320-78fb-432b-9b14-a90285a8a1e1)

![cat4](https://github.com/user-attachments/assets/4b1c091e-6811-4181-b3f8-bbe766a292d0)

![gal5](https://github.com/user-attachments/assets/1227c0b9-7dc1-44e9-8bc2-9dfedf501eeb)

![cat5](https://github.com/user-attachments/assets/7babbaaf-0620-4a75-ba69-ff5fa73f1140)


# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
