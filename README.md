## Index.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width, initial-scale=1.0">
    <title>Dribble</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px;
            background-color: black;
            color:white;
        }

        .second{
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px;
            background-color:grey;
            color:white;
        }
        
        
        

        .navbar li {
            list-style: none;
            display: inline-block;
            margin: 0 10px;
            
        }

        .navbar li a {
            text-decoration: none;
            color: white;
            text-transform: uppercase;
            
            
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        
        .shots {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
}

.shot {
    background-color: white;
    padding: 10px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.shot:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
}

.shot img {
    width: 100%;
    border-radius: 10px;
}

.shot-info {
    display: flex;
    justify-content: space-between;
    margin-top: 10px;
}

.title {
    font-size: 16px;
    font-weight: bold;
}

.likes {
    font-size: 14px;
    color: #ea4c89;
}

    </style>
</head>
<body>
    <div class="header">
        <div class="logo">Dribble</div>
        <div class="navbar">
            <ul>
                <li><a href="shots.html">Shots</a></li>
                <li><a href="designers.html">Designers</a></li>
                <li><a href="teams.html">Teams</a></li>
                <li><a href="community.html">Community</a></li>
                <li><a href="jobs.html">Jobs</a></li>
            </ul>
        </div>
        <div class="search">
            <a href="#"> <button class="btn">Sign Up</button></a>
            <a href="#"> <button class="btn">Sign In</button></a>
            <input class="srch" type="search" name="" placeholder="Search">
            
        </div>
    </div>
    
        <div class="second">

            <p><b>What are you Working On?</b> Dribble is Show and Tell for Designers. </p>
            <a href="#" style="padding-left: 4px;"> <button class="btn1">Learn More</button></a>
            <br>
            <a href="#" style="padding-left: 4px;"> <button class="btn2">Sign In</button></a>

        </div>
        <section class="shots">
        
        <div class="shot">
            <img src="D:\cssAdvanced\famous.jpeg" alt="Shot 1">
            <div class="shot-info">
                <div class="title">Famous</div>
                <div class="likes">❤ 4,044</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\bb1.jpeg" alt="Shot 2">
            <div class="shot-info">
                <div class="title">Balkan Brothers</div>
                <div class="likes">❤ 2,404</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\jan.jpeg" alt="Shot 3">
            <div class="shot-info">
                <div class="title">Jan Losert</div>
                <div class="likes">❤ 3,985</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\mati.jpeg" alt="Shot 4">
            <div class="shot-info">
                <div class="title">Mattias Johansson</div>
                <div class="likes">❤ 2,602</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\rus.jpeg" alt="Shot 5">
            <div class="shot-info">
                <div class="title">Ruslan Siiz</div>
                <div class="likes">❤ 2,369</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\pp.jpeg" alt="Shot 6">
            <div class="shot-info">
                <div class="title">Paperpillar</div>
                <div class="likes">❤ 1,022</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\lucas.jpeg" alt="Shot 7">
            <div class="shot-info">
                <div class="title">lucas fields</div>
                <div class="likes">❤ 5,414</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\haloo.jpeg" alt="Shot 8">
            <div class="shot-info">
                <div class="title">Hallo Lab</div>
                <div class="likes">❤ 4,237</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\rv.jpeg" alt="Shot 9">
            <div class="shot-info">
                <div class="title">Rv Studio</div>
                <div class="likes">❤ 1,845</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\nixito.jpeg" alt="Shot 10">
            <div class="shot-info">
                <div class="title">nixtio</div>
                <div class="likes">❤ 7,175</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\lain.jpeg" alt="Shot 11">
            <div class="shot-info">
                <div class="title">Lain</div>
                <div class="likes">❤ 4,272</div>
            </div>
        </div>
        <div class="shot">
            <img src="D:\cssAdvanced\stevan.jpeg" alt="Shot 12">
            <div class="shot-info">
                <div class="title">Stevan Rodic</div>
                <div class="likes">❤ 4,527</div>
            </div>
        </div>
        
        
            </div>
        </div>
    </section>

      
    
</body>
</html>

```

## Output

![image](https://github.com/AshikaJubi/css-advanced/assets/129098066/b155f9e9-649b-41e1-8829-447fab142466)
