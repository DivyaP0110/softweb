# Ex.07 Software Product Company Website
## Date: 15-12-2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home1.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:rgb(0, 128, 38);
            color:white;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:60%;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: rgb(38, 0, 255);
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:teal;
        
        }
        .heading1{
            color:black;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:rgb(7, 1, 19);
            text-align: justify;
            font-size: 30px;
            font-family:'Arial Narrow Bold';
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
        .bottomdiv{
            background-color:rgb(0, 128, 34);
            color:white;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 72px;
            font-size: xx-large;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1>
                DEVICE DELIGHT
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
"Everything
you need to build
your business"

Explore our all-access membership<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                            Username:
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            Password:
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: black; color:rgb(0, 255, 0);">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Divya P (23002600)</p>
    </div>
</body>
<html>

products.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(174, 70, 86);
            color:white;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
            font-size: x-large;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:rgb(201, 189, 189);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(101, 137, 144);
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            font-family:'Times New Roman'
            color:rgb(93, 0, 255);
        }
        .bottomdiv{
            background-color:rgb(94, 128, 0);
            color:white;
            text-align: center;
            font-family:'Georgia';
            font-size: x-large;
            position:relative;
            display:block;
            margin-top: 56px;

        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DEVICE DELIGHT</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
                <img src="autocad.jpeg">
                <h1>AutoCad</h1>
                <p>AutoCAD is computer-aided design (CAD) software that is used for precise 2D and 3D drafting, design, and modelling with solids, surfaces, mesh objects, documentation features, and more.</p>
            </div>
            <div class="box">
                <img src="adobe photoshop.png">
                <h1>Adobe Photoshop</h1>
                <p>It is widely used for image editing, retouching, creating image compositions, website mockups, and adding affects. Digital or scanned images can be edited for use online or in-print. Website layouts can be created within Photoshop; their designs can be finalized before developers move on to the coding stage.</p>
            </div>
            <div class="box">
                <img src="app store.jpeg">
                <h1>App Store</h1>
                <p>The App Store is an app marketplace developed and maintained by Apple Inc., for mobile apps on its iOS and iPadOS operating systems. The store allows users to browse and download approved apps developed within Apple's iOS SDK. </p>
            </div>
            <div class="box">
                <img src="word.png">
                <h1>Microsoft Word</h1>
                <p>Read and edit documents attached to emails, collaborate with your team and bring your office wherever you go with Microsoft Word. The Word app from Microsoft lets you create, read, edit, and share your files quickly and easily. Word introduces a mobile PDF reader for your phone.</p>
            </div>
            <div class="box">
                <img src="github.png">
                <h1>Github</h1>
                <p>GitHub, Inc. is a platform and cloud-based service for software development and version control, allowing developers to store and manage their code.</p>
            </div>
            <div class="box">
                <img src="brainly.png">
                <h1>Brainly</h1>
                <p>Brainly is a Polish Multinational company based in Kraków, Poland, with headquarters in New York City. It is an AI-powered homework help platform targeting students and parents. As of November 2020, Brainly reported having 15 million daily active users, making it the world's most popular education app.</p>
            </div>
            <div class="box">
                <img src="siri.jpeg">
                <h1>Siri</h1>
                <p>Siri learns what you need. Not who you are. What you ask Siri isn't associated with your Apple ID. The power of the Apple Neural Engine ensures that the audio of your requests never leaves your iPhone, iPad or Apple Watch unless you choose to share it.</p>
            </div>
            <div class="box">
                <img src="chatgpt.png">
                <h1>Chat gpt</h1>
                <p>ChatGPT is a chatbot developed by OpenAI and launched on November 30, 2022. Based on a large language model, it enables users to refine and steer a conversation towards a desired length, format, style, level of detail, and language.</p>
            </div>
        </div>
    </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Divya P (23002600)</p>
    </div>
</body>
</html>

person.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:white;
            padding: 15px;
            font-family: 'Trebuchet MS';
            font-size: larger;
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:rgb(255, 255, 255);
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            font-size: xx-large;
            color:rgb(123, 0, 255);
        }
        .bottomdiv{
            background-color:rgb(94, 128, 0);
            color:rgb(201, 193, 193);
            text-align: center;
            font-family:'Arial Narrow Bold';
            font-size: xx-large;
            position:relative;
            display:block;
            margin-top: 163px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
            font-size: x-large;
        }
        b,p{
            color:rgb(24, 4, 4);
            text-align: center;
        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DEVICE DELIGHT</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="my pic.jpg" class="MyPic">
                </td>
                <td>
                    <img src="Revathi.jpg" class="Revathi">
                </td>
                <td>
                    <img src="Dinesh.jpg" class="Dinesh">
                </td>
                <td>
                    <img src="sk.jpeg" class="Siva">
                </td>
                <td>
                    <img src="einstein.jpeg" class="Einstein">
                </td>
                <td>
                    <img src="kalam.jpeg" class="Abdul Kalam">
                </td>
            </tr>
            <tr>
                <td>
                    <b>Divya</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>Revathi</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b>Dinesh</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Siva</b>
                    <p>CEODirector</p>
                </td>
                <td>
                    <b>Einstein</b>
                    <p>Asst.Director</p>
                </td>
                <td>
                    <b>Abdul Kalam</b>
                    <p>Dy.Director</p>
                </td>
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Divya P(23002600)</p>
    </div>
</body>
</html>
               
contactus.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Contactus</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(0, 128, 17);
            color:white;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(102, 128, 0);
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color: rgb(19, 19, 3);
        }
        .table1{
            color:white;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color: rgb(20, 20, 9);
        }
        .table2{
            color:white;
            font-size: large;
            background-color:rgb(95, 92, 92);
            border-radius: 5px;
            border-style:dotted;
            border-color: rgb(0, 187, 255);

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:rgb(128, 0, 21);
            color:white;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DEVICE DELIGHT</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        Saffron palace,34/55,java street,Coimbatore-641001
                    </td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        near metro station, next to collector office.
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        devicedelight123@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9367538760
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
                            NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: lightskyblue; color: black;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Designed and Developed by Divya P (23002600)</p>
        </div>
    </div>
</body>
</html>


```

## OUTPUT:
![Alt text](<Screenshot (43).png>)
![Alt text](<Screenshot (44).png>)
![Alt text](<Screenshot (45).png>)
![Alt text](<Screenshot (46).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
