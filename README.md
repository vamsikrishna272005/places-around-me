# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone repository from the github.

### Step 2:
Add html files in static folder. Run the python file

## Code:
Include your HTML code here

### map.html:
```html
<!DOCTYPE html>
<html >
<head>
    <title>imagemaps</title>
</head>
<style>
  body{
    background-color: bisque;
    margin-left: 250px;
  }
  h1{
    margin-left: 265px;
  }
</style>
<body>
    <h1>Places around me</h1>
    <img src="tyrimage.jpg" usemap="#Thiruvaiyaru">
<map name="Thiruvaiyaru">
  <area alt="playground" title="playground" href="playground.html" coords="238,330,78" shape="circle">
  <area alt="My home" title="My home" href="myhome.html" coords="170,444,298,516" shape="rect">
  <area alt="Amalraj matric.hr.sec.School" title="Amalraj matric.hr.sec.school" href="school.html" coords="22,35,191" shape="circle">
  <area alt="Andavar halwa shop" title="Andavar halwa shop" href="shop.html" coords="343,173,484,262" shape="rect">
  <area alt="Big temple" title="Big temple" href="temple.html" coords="434,35,722,174" shape="rect">
</map>
</body>
</html>
```

### myhome.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>My home</title>
</head>
<style>
    *{
        margin: 0%;
        padding: 0%;
        font-family: sans-serif;
    }
    body{
        background-color: blueviolet;
    }
    .align{
        margin: 75px auto;
        width: 70%;
    }
    img{
        float: left;
        max-width: 55%;
        border: 3px solid rgb(8, 8, 8);
        border-radius: 20px;
        margin-right: 15px;
    }
    .text h2{
        font-size: xx-large;
        font-weight: bolder;
        color: bisque;
    }
    .text p{
        padding-top: 10px;
        font-size: large;
        font-weight: 500;
        color: aliceblue;
    }
</style>
<body>
    <div class="align">
        <img style="" src="home.jpg" alt="view">
        <div class="text">
            <h2>My Home: A Place of Nature and Peace</h2>
    <p>The view from my home is my absolute favourite. It fills me with joy and peace.
         Similarly, everyone cherishes their home and has a favorite view that they adore.My home is near the river, where I can hear the soothing sound of water. It is surrounded by more trees, which provide me with fresh air and shade. There is a feel of natural environment, which makes me calm and happy.
         My house is far from the main town, so there is no much unwanted noise. 
         I can enjoy the peace and tranquility of my home.</p>
           </div>
        </div>
</body>
</html>
```
### ground.html:
```html
          <h2>My Playground: A Place of Sports and Fun.</h2>
    <p>This is my vast playground, where I play badminton and cricket. 
        I love both these sports, as they keep me fit and happy. 
        Since I am a badminton player, I often go to the ground early in the morning with my brothers and friends. 
        We enjoy playing in the cold weather, when we feel shivering and the early snowdrops. 
        I like all these, as they give me relaxation, more energy and confidence for the whole day. 
        I play cricket in the evening after my school. 
        It is more fun, as we have teams and competitions. 
        We cheer and celebrate each other's victories.</p>
```
### school.html:
```html
<h2>My School: A Place of Wisdom and Friendship</h2>
    <p>This is my school, where I build myself for 17 years. 
        It is a place of wisdom, where I learn from the best teachers and books. 
        They teach me not only the academic subjects, but also the values and skills that I need in life. 
        We all have many friends, but the childhood friends are a little more special. 
        They are the ones who share our joys and sorrows, our dreams and fears. 
        They are the friends I found in this place, where we have fun and support each other. 
        I enjoyed a lot in my school days and it is always memorable and last for the rest of my life. 
        I have many stories and experiences that I can cherish and share. 
        I am very proud to be part of my school, which has shaped me into who I am today.
```
### temple.html:
```html
   <h2>My Favourite Temple: A Place of History and Devotion</h2>
    <p>This is my favourite temple in my area. It is a place of worship and silence. Inside the temple, there is a pin drop silence that is maintained by the devotees. 
        The temple is adorned with many sculptures and rare statues that depict the gods and goddesses. The temple has four entry points, each leading to a different sanctum. It is one of the oldest temples in the region. The oldest parts of the present masonry structure were built during the Chola dynasty in the 9th century.
         The temple is famous for the festival called sabthasthanam, which is held every year with pride and devotion.
         The festival involves the procession of the deities to seven other temples in the vicinity.</p>
```
### shop.html:
```html
<h2>Ashoka Halwa: A Traditional and Tasty Snack</h2>
    <p>This is my area's famous snack. 
        I love the taste of this food very much. 
        This name is ashoka halwa. It is a traditional food for us. 
        Ashoka halwa is a delicious, glossy dessert made with moong dal, sugar, ghee, wheat flour, and cardamom. 
        It has a smooth and melt-in-mouth texture that makes it irresistible. 
        Ashoka halwa is a speciality of Thiruvaiyaru, a town in Thanjavur district of Tamil Nadu. 
        It is also known as pasi paruppu halwa or asoka halwa. 
        It is usually prepared for festivals, weddings, and other occasions. 
        It is served hot or warm, garnished with cashew nuts. 
        Ashoka halwa is one of my favourite sweets and I enjoy it whenever I get a chance.
    </p>
```
## Output:
Include your output screenshot here

![imagemaps output](./Placesaroundmeoutput.jpg)

## Result:
The program is executed successfully.