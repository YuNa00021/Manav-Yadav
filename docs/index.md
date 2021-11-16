<!DOCTYPE html>
<html lang="en">
<head>
  <title>Lamborghini</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@202;350;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@202;350;700&family=Libre+Barcode+39+Extended&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@202;350;700&family=Libre+Barcode+39+Extended&family=Monoton&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bungee&family=Josefin+Sans:wght@202;350;700&family=Libre+Barcode+39+Extended&family=Monoton&display=swap');

  html {
    background-color:rgb(25,25,25);
    user-select:none;
  } 
  .logo {
    height:80px;
    width:75px;
    position:absolute;
    top:10px;
    left:10px;
  }
  .back-text {
    font-family:'Josefin Sans', sans-serif;
    color:#808080;
    font-weight:700;
    font-size:100px;
    opacity:0.15;
    letter-spacing:-5px;
    position:absolute;
    top:280px;
    left:210px;
    user-select:none;
  }
  .car {
    width:600px;
    height:200px;
    position:absolute;
    top:290px;
    left:310px;
    user-select:none;
  }
  .head {
    color:white;
    font-family:'Josefin Sans', sans-serif;
  }
    .head {
    color:white;
    font-family:'Josefin Sans', sans-serif;
    user-select:none;
    font-size:30px;
    letter-spacing:2px;
    position:absolute;
    top:100px;
    left:450px;
    }  
    
  .head span {
    color:#ea0f6b;
    font-family:'Josefin Sans', sans-serif;
    user-select:none;
    font-size:50px;
    letter-spacing:2px;
    position:absolute;
    top:-15px;
    margin-left:10px;
    }
    .btn {
      background-color:#ea0f6b;
      color:white;
      border:none;
      height:40px;
      width:100px;
      font-family:;
      border-radius:25px;
      position:absolute;
      top:180px;
      left:530px;
      cursor:pointer;
      transition:0.15s;
    }
    .btn:hover {
      background-color:#ea0f6b;
      outline:2px solid #ea0f6b;
      outline-offset:2px;
    }
    .twitter {
      color:grey;
      height:30px;
      width:30px;
      position:absolute;
      bottom:30px;
      left:30px;
      transition:0.25s;
    }
    .facebook {
    color:grey;
    height:30px;
    width:30px;
    position:absolute;
    bottom:30px;
    left:80px;
    transition:0.25s;
    }
    .youtube {
    color:grey;
    height:30px;
    width:30px;
    position:absolute;
    bottom:30px;
    left:130px;
    transition:0.25s;
    }
    .twitter:hover, .facebook:hover, .youtube:hover {
      color:#ea0f6b;
    }
    .head-links {
      list-style:none;
      color:white;
      text-decoration:none;
      display:flex;
      position:absolute;
      top:15px;
      right:10px;
    }
     .li {
     margin-right:40px;
     font-family:'Josefin Sans', sans-serif;
     font-weight:350;
     transition:0.25s;
     cursor:pointer;
     text-decoration:none;
     }
     .li:hover {
     color:#ea0f6b;
     }
     .li {
       text-decoration:none;
       color:white;
     }
     .bar-code {
       color:grey;
       font-family: 'Libre Barcode 39 Extended', cursive;
       font-size:35px;
       position:absolute;
       right:30px;
       bottom:-15px;
     }
     .text-code-bar {
       color:grey;
       font-family:'Josefin Sans', sans-serif;
       font-size:15px;
       font-weight:400;
       opacity:0.29;
       position:absolute;
       right:60px;
       bottom:45px;
     }
     .name {
       font-family: 'Monoton', cursive;
       color:grey;
       font-size:50px;
       opacity:0.35;
       position:absolute;
       top:430px;
       left:420px;
     }
     .features {
       position:absolute;
       color:white;
       top:104%;
       font-family:'Josefin Sans', sans-serif;
       width:40%;
       left:50px;
     }
     .features h2 {
       color:#ea0f6b;
     }
     .details {
       position:absolute;
       width:60%;
       top:0%;
       right:-100%;
     }
     .line {
       width:230%;
     }
     .name-contact, .email-contact, .message-contact {
       background:none;
       color:white;
       border:none; 
       outline: 2px solid white;
       outline-offset:10px;
       border-radius:0px
     }
     .name-contact {
       position:absolute;
       top:107%;
       left:400px;
     }
     .email-contact {
       position:absolute;
       top:107%;
       left:600px;
     }
     .message-contact {
       position:absolute;
       top:112%;
       left:400px;
       font-family:arial;
       resize:none;
       height:100px;
       width:363px;
     }
     .contact h2 {
       position:absolute;
       left:525px;
     }
     .send-btn {
     position:absolute;
     top:123%;
     left:720px;
     background-color:transparent;
     color:white;
     border:none;
     border-radius:0px;
     outline:2px solid white;
     outline-offset:7px;
     }
     .line-last {
     width:230%;
     position:absolute;
     top:130%;
     }
</style>
</head>

<body>
  <ul class="head-links">
    <li><a href="#fea" class="li">Features</a></li>
    <li><a href="#stor" class="li">Store</a></li>
    <li><a href="#con" class="li">Contact</a></li>
    <li><a class="li" href="https://embed.spck.io/run/idb/Lamborghini%20Website%20White/index.html">Day Mode</a></li>
  </ul>
  
  
  <img class="logo" src="logo.png">
  <p class="name">AVENDATOR</p>
  <h1 class="back-text">RACING GROUND</h1>
  <h1 class="head">READY TO <span>RACE</span></h1>
  <button class="btn">RIDE NOW</button>
  <img draggable="false" class="car" src="avendator.png">
  <a href="#"><ion-icon class="twitter" name="logo-twitter"></ion-icon></a>
  <a href="#"><ion-icon class="facebook" name="logo-facebook"></ion-icon></a>
  <a href="#"><ion-icon class="youtube" name="logo-youtube"></ion-icon></a>
  <p class="bar-code">Avendator</p>
  <p class="text-code-bar"><b>BAR CODE OF LAMBORGHINI</b></p>
  
    <div class="features">
      <div id="fea"></div>
      <h2>FEATURES</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Dui ut ornare lectus sit amet est. Vitae turpis massa sed elementum tempus egestas. Sit amet nulla facilisi morbi tempus iaculis urna id. Urna molestie at elementum eu. At urna condimentum mattis pellentesque id nibh tortor. Odio eu feugiat pretium nibh ipsum. Eget sit amet tellus cras adipiscing enim. Et sollicitudin ac orci phasellus egestas tellus rutrum tellus pellentesque. Pellentesque sit amet porttitor eget. Tincidunt lobortis feugiat vivamus at augue eget arcu dictum varius. Condimentum id venenatis a condimentum vitae sapien. Mattis vulputate enim nulla aliquet porttitor lacus luctus. Maecenas ultricies mi eget mauris pharetra et ultrices. Aliquet sagittis id consectetur purus ut faucibus. Iaculis urna id volutpat lacus. Consectetur adipiscing elit duis tristique sollicitudin. Amet purus gravida quis blandit. Turpis in eu mi bibendum.
      <br>
      <br>
      <br>
      At tempor commodo ullamcorper a. Tellus pellentesque eu tincidunt tortor aliquam. Arcu cursus euismod quis viverra nibh cras pulvinar. Id diam maecenas ultricies mi eget mauris pharetra. Integer enim neque volutpat ac tincidunt. Sollicitudin aliquam ultrices sagittis orci a. Ornare arcu odio ut sem nulla pharetra. Volutpat lacus laoreet non curabitur gravida. Purus faucibus ornare suspendisse sed nisi lacus. Morbi leo urna molestie at elementum eu. Sed adipiscing diam donec adipiscing. Dignissim convallis aenean et tortor at risus.
      <br>
      <br>
      <br>
      Nunc sed id semper risus in hendrerit gravida rutrum quisque. Diam vel quam elementum pulvinar etiam non quam. Tellus molestie nunc non blandit massa enim nec. Dolor sed viverra ipsum nunc aliquet. Facilisi nullam vehicula ipsum a arcu cursus vitae congue. Risus in hendrerit gravida rutrum quisque non tellus orci. Auctor elit sed vulputate mi sit amet mauris commodo. Suspendisse potenti nullam ac tortor vitae purus faucibus ornare suspendisse. Nulla facilisi etiam dignissim diam quis enim lobortis scelerisque fermentum. Morbi tristique senectus et netus et malesuada fames ac turpis. Quam viverra orci sagittis eu. Morbi tincidunt ornare massa eget egestas purus viverra. Tellus at urna condimentum mattis pellentesque id nibh tortor id. Urna et pharetra pharetra massa massa. Praesent tristique magna sit amet purus gravida. Nascetur ridiculus mus mauris vitae ultricies. Non enim praesent elementum facilisis leo vel. Augue lacus viverra vitae congue eu consequat. Bibendum arcu vitae elementum curabitur vitae nunc sed velit.
      <br>
      <br>
      <br>
      Enim nulla aliquet porttitor lacus luctus accumsan tortor posuere. Egestas pretium aenean pharetra magna ac placerat vestibulum lectus mauris. Iaculis eu non diam phasellus vestibulum. Curabitur gravida arcu ac tortor dignissim convallis. Nec feugiat nisl pretium fusce id velit. Velit ut tortor pretium viverra suspendisse potenti nullam ac tortor. Viverra adipiscing at in tellus integer feugiat scelerisque varius morbi. Blandit cursus risus at ultrices mi. Integer quis auctor elit sed vulputate mi sit amet. Consectetur adipiscing elit duis tristique sollicitudin.
      <br>
      <br>
      <br>
      Sollicitudin tempor id eu nisl nunc mi ipsum faucibus vitae. Neque vitae tempus quam pellentesque nec nam aliquam sem. Dui faucibus in ornare quam viverra orci. Fermentum leo vel orci porta non pulvinar. Est velit egestas dui id ornare. Metus aliquam eleifend mi in nulla posuere sollicitudin aliquam. Nunc consequat interdum varius sit amet mattis vulputate. Eu feugiat pretium nibh ipsum consequat nisl vel. Et netus et malesuada fames ac turpis. Enim nec dui nunc mattis enim ut tellus elementum. Nec sagittis aliquam malesuada bibendum arcu vitae. Congue nisi vitae suscipit tellus mauris a.</p>
      
      <div class="details">
        <h2>More Details</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Mauris rhoncus aenean vel elit scelerisque mauris. Vestibulum lectus mauris ultrices eros. At augue eget arcu dictum. Enim blandit volutpat maecenas volutpat blandit. Sagittis nisl rhoncus mattis rhoncus. Malesuada fames ac turpis egestas sed tempus urna et pharetra. Pellentesque eu tincidunt tortor aliquam nulla facilisi cras. Imperdiet massa tincidunt nunc pulvinar. Elit duis tristique sollicitudin nibh sit amet commodo nulla facilisi. Dignissim suspendisse in est ante in nibh mauris cursus mattis. Ut sem nulla pharetra diam sit amet nisl. Nibh sed pulvinar proin gravida hendrerit lectus a. Egestas diam in arcu cursus euismod quis. Sem integer vitae justo eget magna fermentum iaculis eu non. Ornare arcu odio ut sem nulla pharetra.
        <br>
        <br>
        <br>
        Nisi lacus sed viverra tellus in hac habitasse platea dictumst. Pharetra vel turpis nunc eget lorem dolor sed viverra. Eros in cursus turpis massa tincidunt dui ut ornare lectus. Aliquam ultrices sagittis orci a scelerisque purus semper eget duis. Vitae aliquet nec ullamcorper sit amet. Arcu odio ut sem nulla. Sed viverra ipsum nunc aliquet bibendum enim facilisis. Pellentesque dignissim enim sit amet venenatis urna cursus eget nunc. Pellentesque diam volutpat commodo sed egestas egestas fringilla phasellus faucibus. Ultricies mi eget mauris pharetra. Neque gravida in fermentum et sollicitudin ac orci phasellus. At imperdiet dui accumsan sit amet nulla facilisi morbi. Netus et malesuada fames ac turpis egestas. Euismod quis viverra nibh cras pulvinar mattis nunc. Enim tortor at auctor urna nunc. Nec tincidunt praesent semper feugiat nibh. Nullam ac tortor vitae purus faucibus ornare suspendisse sed nisi. Amet commodo nulla facilisi nullam vehicula ipsum. Ipsum dolor sit amet consectetur adipiscing elit pellentesque. Commodo quis imperdiet massa tincidunt nunc pulvinar sapien.</p>
        <div id="stor"></div>
      </div>
      <div class="stores">
        <hr class="line">
        <h2>Stores Near By You</h2>
        <p>
          <ion-icon name="pin"></ion-icon> Showroom #21 , Sector 21 , Panchkula <br><br>
          <ion-icon name="pin"></ion-icon> NH 21 , Zirakpur <br><br>
          <ion-icon name="pin"></ion-icon> Opposite of Solitaire School , Mohali
        </p>
      </div>
      <div class="contact">
        <hr class="line">
        <h2>Contact</h2>
        <div id="con"></div>
        <input class="name-contact" placeholder=" Your Name" required>
        <input class="email-contact" placeholder=" Your Email" required>
        <textarea class="message-contact" placeholder=" Your Message" required></textarea>
        <button class="send-btn">SEND</button>
        <hr class="line-last">
      </div>
  <script src="https://unpkg.com/ionicons@4.5.10-0/dist/ionicons.js"></script>
</body>
</html>
