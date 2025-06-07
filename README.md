<!DOCTYPE html>
<html>
<head>
 <title>The Monk Diamond</title>
</head>
<body>
 <p>The Monk Diamond is a rare jewel.</p>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>The Monk Diamond</title>
</head>
<body>
 <p>The Monk Diamond has been discovered in Siberia.<br/>
    Professor Bairstone and Dr Day were on a fossil-finding expedition.</p>
 <p>Ernest, Professor Bairstone's dog, found the jewel.</p>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>The Monk Diamond</title>
</head>
<body>
 <p>The Monk Diamond is a rare green color. </p>
 <img src="FILENAME.jpg" alt="The Monk Diamond"/>
 <p>The team was delighted with their discovery.</p>
 <img src="URL" alt="The Team"/>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>The Monk Diamond</title>
</head>
<body>
 <div>
  <p>Professor Bairstone is a famous explorer.</p>
 </div>
 <div>
  <p>Dr Day is a top scientist. She loves dinosaur fossils.</p>
 </div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>The Monk Diamond</title>
</head>
<body>
 <div style="background-color: pink;">
  <p>The jewel was stolen from Moscow.</p>
  <p>The theft happened three years ago.</p>
 </div>
 <div style="background-color: pink;">
  <p>The Bond Brothers are the prime suspects.</p>
 </div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>The Monk Diamond</title>
</head>
<body>
 <div style="color: green; font-size: 18pt; text-align: center;">
  Why was the diamond hidden in a cave?<br/>
  Who hid it there?
 </div>
 <div style="width: 75%; height: 100px; background-color: lightblue; margin: 20px;">
  Was it the Bond Brothers?<br/>
  Could they be watching the cave?
 </div>
 <div style="float: right; border: 6px dotted red; padding: 20px;">
  Is the team safe?<br/>
  Their camp is very remote.
 </div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>The Monk Diamond</title>
 <style>
  .header {
    background-color: lightblue;
    padding: 25px;
    text-align: center;
    font-size: 18pt;
    width: 100%;
    height: 25%;
  }
  .title {
    font-size: 14pt;
    text-align: center;
    color: green;
  }
  .body {
    margin: 20px;
  } 
 </style>
</head>
<body>
 <div class="header">
  The Monk Diamond<br/>
  An incredible discovery
 </div>
 <br/>
 <div  class="title">
  Stolen diamond found on expedition in Siberia!
 </div>
 <br/>
 <div class="body">
   Professor Bairstone and Dr Day were looking for fossils in Siberia.<br/>
   They found the stolen diamond hidden inside a remote cave.
 </div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Links</title>
</head>
<body>
 <a href="https://www.google.co.uk">Click here</a>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Page 1</title>
</head>
<body>
 <a href="page2.html">Page 2</a>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Variables</title>
</head>
<body>
 <script>
  var diamondCarats = 300;
  alert(diamondCarats);
  var teamMembers = 2 + 1;
  alert(teamMembers);
  var jewelThieves = "The Bond Brothers";
  alert(jewelThieves);
 </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Conditionals</title>
</head>
<body>
 <script>
  var dogName = "Ernest";
   if(dogName == "Ernest") {
   alert("You discovered the Monk Diamond!");
  }
 </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Conditionals</title>
</head>
<body>
 <script>
  var diamondValue = 10;
  if(diamondValue <= 9.9) {
   alert("Value: Under £10 million!");
  }
  else {
   alert("Value: Over £10 million!");
  }
 </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Functions</title>
</head>
<body>
 <script>
  function checkAccess() {
   return "Expedition team only!";
  }
  var webPage = checkAccess();
  alert(webPage);
 </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Onclick</title>
</head>
<body>
 <a href="https://www.google.com" onclick="alert('Redirecting to Google');">
  Google
 </a>
 <br/>
 <a href="https://www.google.com" onclick="return false;">
  Google
 </a>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>To-Do List App</title>
 <style>
  input[type="button"] {
   background-color: pink;
  }
 </style>
</head>
<body>
 <p>Special Exhibition To-Do List</p>
 <br/>
 <input type="text" value="Type here to add task"/>
 <br/>
 <input type="button" value="Add item"/>
 <br/>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>To-Do List App</title>
 <script>
  function addItem() {
   alert("Hire security team!");
  }
</script>
</head>
<body>
 <p>Special Exhibition To-Do List App</p>
 <br/>
 <input type="text" value="Type here to add task"/>
 <br/>
 <input type="button" value="Add item" onclick="addItem();"/>
 <br/>
 </body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Methods</title>
 <script>
  function addItem() {
   document.getElementById("container").innerHTML = "Item to remember";
  }
 </script>
</head>
<body>
 <input type="button" value="Add item" onclick="addItem();"/>
 <div id="container"></div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>New Elements</title>
 <script>
  function addItem() {
   var newItem = document.createElement("div");
   newItem.innerHTML = "New item";
   document.getElementById("list").appendChild(newItem);
  }
 </script>
</head>
<body>
 <div id="list" onclick="addItem();">Click here to add item</div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>To-Do List App</title>
 <script>
  function addItem() {
   var newItem = document.createElement("div");
   newItem.innerHTML = document.getElementById("box").value;
   document.getElementById("list").appendChild(newItem);
  }
 </script>
</head>
<body>
 <p>Special Exhibition To-Do List</p>
 <br/>
 <input type="text" id="box" value="Type here to add task"/>
 <br/>
 <input type="button" value="Add item "onclick="addItem();"/>
 <br/>
 <div id="list"></div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Remove Items</title>
 <script>
  function removeItem(item) {
   document.getElementById("list"). removeChild(item);
  }
 </script>
</head>
<body>
 <div id="list">
  Security to protect Mr Volkov
   <div onclick="removeItem(this);">
     Woolly socks
   </div>
 </div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>To-Do List App</title>
 <script>
  function addItem() {
   var newItem = document.createElement("div");
    newItem.innerHTML = document.getElementById("box").value;
    newItem.onclick = removeItem;
    document.getElementById("list").appendChild(newItem);
   }
  function removeItem() {
   document.getElementById("list").removeChild(this);
  }
 </script>
</head>
<body>
 <p>Special Exhibition To-Do List</p>
 <br/>
 <input type="text" id="box" value="Type here to add task"/>
 <br/>
 <input type="button" value="Add item" onclick="addItem();"/>
 <br/>
 <div id="list"></div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Storage</title>
 <script>
  function save() {
   var newItem = document.getElementById("box").value;
   localStorage.box = newItem;
  }
  function load() {
   var savedDiv = document.getElementById("savedList");
   savedDiv.innerHTML = localStorage.box;
  }
</script>
</head>
<body>
 <input type="text" id="box" value="Type here to add task"/><br/>
 <input type="button" id="save" value="Save" onclick="save();"/><br/>
 <input type="button" id="load" value="Load" onclick="load();"/><br/>
  Saved item: <div id="savedList"></div>
</body>
</html>
<iframe
  width="600"
  height="450"
  style="border:0"
  loading="lazy"
  allowfullscreen
  referrerpolicy="no-referrer-when-downgrade"
  src="https://www.google.com/maps/embed/v1/place?key=API_KEY
    &q=Space+Needle,Seattle+WA">
</iframe>
<!DOCTYPE html>
<html>
<head>
 <title>iFrames</title>
</head>
<body>
 <iframe
  width="350px"
  height="350px"
  frameborder="0px"
  style="border: 0px"
  src="http://www.bing.com">
 </iframe>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>City Map</title>
</head>
<body>
 <iframe
  width="450px"
  height="450px"
  frameborder="0px"
  style="border: 0px"
  src="https://www.google.com/maps/embed/v1/search?q=Moscow&key=API-KEY">
 </iframe>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Timers</title>
 <script>
  var count = 0;
  function updateCount() {
   count = count + 1;
   document.getElementById("number").innerHTML = count;
   setTimeout(updateCount, 1000);
  }
 </script>
</head>
<body>
 <div id="number">
 </div>
 <script>
  updateCount();
 </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Display</title>
</head>
<body>
 <div>Security</div>
 <div style="display: none;">Thief</div>
 <div>Guest</div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>Security Game</title>
 <style>
  #board {
   border: 1px solid black;
   background-color: gray;
   height: 350px;
   width: 650px;
  }
  .character {
   background-color: lightblue;
   width: 120px;
   height: 120px;
   padding: 10px;
   margin: 10px;
        float: left;
  }
  .hidden {
   display: none;
  }
  .visible {
   display: block;
   }
 </style>
</head>
<body>
 <input type="button" value="Play" onclick="startGame()";/>
 <div id="board">
  <div class="character">1</div>
  <div class="character">2</div>
  <div class="character">3</div>
  <div class="character">4</div>
  <div class="character">5</div>
  <div class="character">6</div>
 </div>
 <script>
  function startGame() {
   gameLoop();
  }
  var loops = 0;
  var peopleVisible = false;
  function gameLoop() {
   peopleVisible = !peopleVisible;
   flashCharacters();
   loops++;
   if(loops < 12) {
    setTimeout(gameLoop, 3000);
   }
   else {
   alert("Game over!");
   }
 }
  function flashCharacters() {
   var board = document.getElementById("board");
   var classToSet = peopleVisible ? "character visible" : "character hidden";
   for(var index = 0; index < 6; index++) {
    board.children[index].className = classToSet;
  }
 }
 </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Home</title>

    <style>
        body {
            margin: 0px;
            padding: 0px;
            border: 0px;
            background-color: #08E8FF;
            color: white;
        }

        a {
            color: white;
        }

        .header {
            height: 65px;
            margin-top: 25px;
            text-align: center;
            font-size: 24px;
        }

        .banner {
            background: url(diamond.jpg);
            background-size: cover;
            width: auto;
            height: 400px;
            text-align: center;
            font-size: 52px;
            padding-top: 75px;
            color: white;
        }

        .content {
            min-height: 500px;
            padding: 50px;
            font-size: 18px;
            background-color: white;
            color: black;
        }

        .footer {
            width: 100%;
            height: 120px;
            padding: 50px;
            text-align: center;
            font-size: 20px;
      color: #1806E8;
        }

        .button {
            text-align: center;
            background-color: #10FF7F;
            color: white;
            margin-left: 43%;
            margin-right: 43%;
            padding: 25px;
        }
    </style>
</head>
<body>
<div class="banner">
    The Monk Diamond<br/>
    <div style="font-size: 32px;">An extraordinary exhibition</div>
</div>
<div class="header">
    <a href="index.html">Home</a>/ <a href="diamond.html">The Diamond</a> / <a href="discovery.html">Discovery</a> / <a href="exhibition.html">Exhibition</a> / <a href="volkov.html">The House of Volkov</a>
</div>
<div class="content">
    <p>The Monk Diamond is one of the rarest and most valuable diamonds in Europe.<br/>
      It has a fascinating history. It was owned by Russian nobility, stolen by a famous criminal gang
        and then found hidden in remote mountains in one of the most sensational discoveries of
        the century.<br/>Find out more about the Monk Diamond in this website or come and see it for
        yourself at the House of Volkov in Moscow.
    </p>

    <p style="padding-top: 50px;">
        <a href="volkov.html" class="button">Visit the House of Volkov</a>
    </p>
</div>
<div class="footer">
    Contact Professor Bairstone: profbairstone@intrepidexplorer.com
</div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>The Diamond</title>

    <style>
        body {
            margin: 0px;
            padding: 0px;
            border: 0px;
            background-color: #08E8FF;
            color: white;
        }

        a {
            color: white;
        }

        .header {
            height: 65px;
            margin-top: 25px;
            text-align: center;
            font-size: 24px;
        }

        .banner {
            background: url(diamond.jpg);
            background-size: cover;
            width: auto;
            height: 200px;
            text-align: center;
            font-size: 52px;
            padding-top: 75px;

            color: white;
        }

        .content {
            min-height: 500px;
            padding-top: 50px;
            padding-bottom: 50px;
            padding-left: 150px;
            padding-right: 150px;
            font-size: 18px;
            background-color: white;
            color: black;
        }

        .footer {
            height: 120px;
            padding: 50px;
            text-align: center;
            font-size: 20px;
      color:#1806E8;
        }
    </style>
</head>
<body>
<div class="header">
    <a href="index.html">Home</a> / <a href="discovery.html">Discovery</a> / <a href="exhibition.html">Exhibition</a> / <a href="volkov.html">The House of Volkov</a>
</div>
<div class="banner">
    The History of the Monk Diamond
</div>

<div class="content">
    <p>The Monk Diamond is famous for its distinctive green colour.<br/>A Russian nobleman bought
        the diamond for his wife in 1889, but it was stolen during the Russian Revolution. For
        the next 30 years, the Monk Diamond’s whereabouts were unknown.<br/>In 1947 it was
        discovered during a police raid on a gang of petty criminals in Moscow.<br/> It was returned
        to the nobleman’s family. The nobleman’s son decided the Monk Diamond was unlucky
        and sold it to the House of Volkov, Moscow’s oldest jewellery house.<br/>The House of Volkov
        paid an undisclosed sum for the jewel, but it was rumoured to be the most expensive diamond sale ever.</p>

    <img src="monkdiamond.jpg" alt="The diamond" style="width: 100%;" />
</div>
<div class="footer">
    Contact Professor Bairstone: profbairstone@intrepidexplorer.com
</div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>The Discovery</title>

    <style>
        body {
            margin: 0px;
            padding: 0px;
            border: 0px;
            background-color: #08E8FF;
            color: white;
        }

        a {
            color: white;
        }

        .header {
            height: 65px;
            margin-top: 25px;
            text-align: center;
            font-size: 24px;
        }

        .banner {
            background: url(diamond.jpg);
            background-size: cover;
            width: auto;
            height: 200px;
            text-align: center;
            font-size: 52px;
            padding-top: 75px;
            color: white;
        }

        .content {
            min-height: 500px;
            padding-top: 50px;
            padding-bottom: 50px;
            font-size: 18px;
            background-color: white;
            color: black;
        }

        .footer {
            height: 120px;
            padding: 50px;
            text-align: center;
            font-size: 20px;
      color:#1806E8;
        }
    </style>
</head>
<body>
<div class="header">
    <a href="index.html">Home</a>/ <a href="diamond.html">The Diamond</a> / <a href="exhibition.html">Exhibition</a> / <a href="volkov.html">The House of Volkov</a>
</div>
<div class="banner">
    The Discovery of the Monk Diamond
</div>

<div class="content">

    <div style="width: 80%; padding-top: 50px; float: left;">
        <p style="padding-left: 50px; padding-right: 50px;">
            Professor Bairstone and Dr Day, along with Ernest the dog, were on an
            expedition in Siberia when they discovered the Monk Diamond.<br/>It had
            been hidden in a remote mountain cave.<br/>The Bond Brothers attempted to
            sabotage the expedition and reclaim the diamond but were unsuccessful.<br/>
            The team returned to Moscow with the diamond and a special exhibition is
            being held at the House of Volkov to celebrate their discovery.
        </p>
    </div>

    <div style="width: 20%; padding-top: 50px; float: left;">
        <img src="diamond.jpg" style="width: 120px;"/>
    </div>

</div>
<div class="footer">
    Contact Professor Bairstone: profbairstone@intrepidexplorer.com
</div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Exhibition</title>

    <style>
        body {
            margin: 0px;
            padding: 0px;
            border: 0px;
            background-color: #08E8FF;
            color: white;
        }

        a {
            color: white;
        }

        .header {
            height: 65px;
            margin-top: 25px;
            text-align: center;
            font-size: 24px;
        }

        .banner {
            background: url(diamond.jpg);
            background-size: cover;
            width: auto;
            height: 400px;
            text-align: center;
            font-size: 52px;
            padding-top: 75px;
            color: white;
        }

        .content {
            min-height: 500px;
            padding: 50px;
            font-size: 18px;
            background-color: white;
            color: black;
        }

        .footer {
            width: 100%;
            height: 120px;
            padding: 50px;
            text-align: center;
            font-size: 20px;
      color: #1806E8;
        }
    </style>
</head>
<body>
<div class="header">
    <a href="index.html">Home</a>/ <a href="diamond.html">The Diamond</a> / <a href="discovery.html">Discovery</a> /<a href="volkov.html">The House of Volkov</a>
</div>
<div class="banner">
    The Special Exhibition
</div>
<div class="content">
    <p style="font-size: 32px; font-weight: bold;">The Special Exhibition</p>
     <p>
        The House of Volkov<br/>
         Opening times
     </p>

    <div>
        Monday to Friday
    </div>
    <div style="margin: 10px;">
        9.30–6.00<br/>
        Last admission 5.30
    </div>
    <div>
        Saturdays and Sundays</div>
    <div style="margin: 10px;">
        11.00–4.00<br/>
        Last admission 3.30</div>
    <div>
        Admission: Free<br/>
        Please note cameras are not allowed inside the House of Volkov.
    </div>

</div>
<div class="footer">
    Contact Professor Bairstone: profbairstone@intrepidexplorer.com
</div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>The House of Volkov</title>

    <style>
        body {
            margin: 0px;
            padding: 0px;
            border: 0px;
            background-color: #08E8FF;
            color: white;
        }

        a {
            color: white;
        }

        .header {
            height: 65px;
            margin-top: 25px;
            text-align: center;
            font-size: 24px;
        }
        .banner {
            background: url(diamond.jpg);
            background-size: cover;
            width: auto;
            height: 200px;
            text-align: center;
            font-size: 52px;
            padding-top: 75px;
            color: white;
        }

        .content {
            min-height: 500px;
            padding-top: 50px;
            padding-bottom: 50px;
            font-size: 18px;
            background-color: white;
            color: black;
        }

        .footer {
            height: 120px;
            padding: 50px;
            text-align: center;
            font-size: 20px;
      color: #1806E8;
        }
    </style>
</head>
<body>
<div class="header">
    <a href="index.html">Home</a>/ <a href="diamond.html">The Diamond</a> / <a href="discovery.html">Discovery</a> / <a href="exhibition.html">Exhibition</a>
</div>
<div class="banner">
    The House of Volkov
</div>

<div class="content">

    <div style="width: 60%; padding-top: 50px; float: left;">
        <p style="padding-left: 50px; font-size: 32px; font-weight: bold;">
            The House of Volkov
        </p>
        <p style="padding-left: 50px; padding-right: 50px;">
            The House of Volkov is the oldest jewellery house in Moscow.<br/>
            Please come and visit us.<br/>
            We are near to St Basil's Cathedral.
        </p>
        <p style="padding-left: 80px;">
            Address:<br/>
            The House of Volkov<br/>
            St Basil's Cathedral<br/>
            Moscow
        </p>
    </div>

    <div style="width: 40%; padding-top: 50px; float: left;">
        <iframe
                width="600"
                height="450"
                frameborder="0" style="border:0"
                src="https://www.google.com/maps/embed/v1/place?key=AIzaSyDmoCE-A_mZ02veBnmtpVEwB1xGELVXDiA&q=St+Basils_Cathedral,Moscow" allowfullscreen>
        </iframe>
    </div>

</div>
<div class="footer">
    Contact Professor Bairstone: profbairstone@intrepidexplorer.com
</div>
</body>
</html>
