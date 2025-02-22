<html>
  <head><meta name="data-remix-projectId" content="11097">
<meta name="data-remix-projectTitle" content="Instruction Challenge">
<meta name="data-remix-projectAuthor" content="khepworth">
<meta name="data-remix-dateUpdated" content="2016-04-08T18:06:26.528Z">
<meta name="data-remix-host" content="https://thimble.mozilla.org">
<meta name="data-remix-readonly" content="null">

    <meta charset="utf-8">

    <!--

Make your own step-by-step guide
================================

This template allows you to build a more advanced step-by-step guide.
The example theme here is for you to change as much as you like to
create appearance and content which are truly your own.

READ THROUGH THE COMMENTS. This is a comment. Everything inside of
this for HTML or '/*' for CSS, is not processed as code, but
instead are just text comments about the code. For this project, the
comments will give you instructions, hints and guides to completing
the project, so skim down through the comments to get an understanding
of what you are being asked to do.

GET ORIENTED IN THE CODE. HTML is made up of tags that look like
this <p> </p>. The tags tell you something about the information
contained between them. Click on the tags in the code on this side
of the editor to get a description of what each tag is for.

IN THIS CHALLENGE, YOU WILL LEARN ABOUT:

- HTML: Nested lists
- HTML: Unordered list
- HTML: Captions
- CSS: Borders
- CSS: Embedding images and videos

-->


    <title>Heather Terzich's Instruction Tips</title>
  <script src="https://thimble.mozilla.org/resources/remix/index.js" type="text/javascript"></script>
</head>
  <body>

    <!--
TASK 1
=======================================================
Replace the header contents: 
- replace logo with an image of your own (100px x 100px and containing transparency). 
- replace 'Firstname Lastname' with your name
- replace 'Name of Site' with a new site name
-->

    <header>          
      <img src=https://www.flickr.com/photos/192881711@N02/51149606491/in/dateposted-public/" title="monogram"><img src="https://live.staticflickr.com/65535/51149606491_730b05445c_b.jpg" width="512" height="360" alt="monogram">            
      <h1>Heather Terzich's Website</h1>
      <h3>How to make a milkshake</h3>

    </header>

    <div class="wrapper">

      <article>            
        <!--
TASK 2
=======================================================
Add your introduction to your step-by-step-guide, including a title, time required to complete the activity, and a rating of how awesome the activity is. 
** Be careful to keep all the HTML tags intact when you are changing the text.
-->         
        <div class="introduction">

          <div class="information">
            <h1>How to make a GREAT milkshake</h1>

            <hr>
            <p><b>Assembly time:</b> 13 minutes<br>
              <b>Awesome rating:</b> 99% awesome</p>
            <hr>

            <p>Have you been wanting to make the best milkshake? It's really fun and easy to make. So try it for yourself? Follow these steps and you'll make an amazing milkshake!</p>

          </div>

          <aside>

            <!--
TASK 3
=======================================================
Add your Things You'll Need. 
** Be careful to keep all the HTML tags intact when you are changing the text.
-->         
            <ul class="list-of-items">
              <li><h2>Things You'll Need</h2></li>
              <li>Cup</li>
              <li>Milk</li>
              <li>Ice Cream</li>
              <li>Blender</li>
              <li>Cookie dough</li>
              <li>Straw</li>
            </ul>
          </aside>
        </div>


        <!--
TASK 4
=======================================================
Add your steps. When you need a new step, copy and paste all of the code of an entire step, then edit the contents.
-->         
        <ol class="step-by-step">

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Pour the milk, ice cream, and cookie dough into the blender.</h3>
              <p>It is important to put the three ingredients into the blender since this is the main step.</p> 
            </div>
          </li>

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Once all three of the ingredients are in the blender go ahead and blend it.</h3>
              <p>Remember, only put enough of the ingredients as you want to drink.</p>

              <!--
This block contains a photo and has a caption.
We have used a <div> to group and position the flickr photo
with a paragraph to create a photo with a caption.
-->
              <a href="https://www.flickr.com/photos/papercherries/5535987923/in/photolist-9rcokD-6eWrim-fWL6eD-2iA96SY-a5ZXFY-rWNZBB-bxUKEr-2hiQkkX-PqTSG2-afESnL-DZypYR-78susn-8cyxj9-fgBAgq-3ogbTh-2kKpmoP-f7mrxc-3tvMd-2gaLY9a-6ms1WQ-4LZioi-3debbQ-48RCiv-6LPg5F-2howHRp-6NTkKr-29CmAdh-7P3koy-7gJx1r-yajLS-XxGy6Y-7gNtyj-2hJKzSm-7fdei3-MeaAP-edm2Kv-8whEf4-2hW9Wqn-2e2P9z-52dbPJ-6hqLCm-2kpD5gW-9UjPjj-L8Kozm-2ib15Dk-5sY8VK-2j93NN2-8EMWsU-5tTwpP-cQfemy" title="milkshakes"><img src="https://live.staticflickr.com/5260/5535987923_defbc48dd3_k.jpg" width="685.5" height="1012" alt="milkshakes"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script> ></a>
              <p class="caption">This is a picture of an ideal milkshake.</p>
            </div>
          </li>

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Pour the blended contents into your cup.</h3>
              <p>It's almost ready to drink.</p>


              <iframe width="560" height="315" src="https://www.youtube.com/embed/pGL2rytTraA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen</iframe>
            </div>

          </li>

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Playing music while making your milkshake is very important.</h3>
              <p>This allows you to have a great time while making a great snack.</p> 
            </div>
          </li>

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Now stick a straw into your perfect milkshake.</h3>
              <p>And dig in!</p> 
            </div>
          </li>



        </ol>

      </article>

    </div>

    <!--
TASK 5
=======================================================
Change the text and links in the footer of this page to acknowledge the sources of your images and youtube videos. If you made all your images and videos, then say so here. 
** NOTE: Broken links will be heavily penalized in grading.
-->         

    <footer>
       <p>The original how-to appeared in https://www.wikihow.com/Make-a-Milkshake title="How to Make a Milkshake - wikiHow">WikiHow </p>
      <p>Images are by https://www.flickr.com/photos/papercherries/5535987923/in/photolist-9rcokD-6eWrim-fWL6eD-2iA96SY-a5ZXFY-rWNZBB-bxUKEr-2hiQkkX-PqTSG2-afESnL-DZypYR-78susn-8cyxj9-fgBAgq-3ogbTh-2kKpmoP-3tvMd-2gaLY9a-6ms1WQ-4LZioi-3debbQ-48RCiv-6LPg5F-2howHRp-6NTkKr-f7mrxc-29CmAdh-7P3koy-7gJx1r-yajLS-XxGy6Y-7gNtyj-2hJKzSm-7fdei3-MeaAP-edm2Kv-8whEf4-2hW9Wqn-2e2P9z-52dbPJ-6hqLCm-2kpD5gW-9UjPjj-L8Kozm-2ib15Dk-5sY8VK-2j93NN2-8EMWsU-5tTwpP-cQfemy title=Milkshake by rosalind, on Flickr">paper cherries from Flickr</p>
    </footer>

    <!--
TASK 6
=======================================================
Customise the visual style and appearance of your guide.
- The CSS below controls all the colors fonts and positioning on this HTML page.
- Be aware, you can break your page quite easily with this part of CSS.
-->         

    <style media="screen" type="text/css">

      /* STRUCTURAL ELEMENTS */

      html {
        position: relative;
        min-height: 100%;
        min-width: 100%;
        width: 100%;
        margin: 0px;
        padding: 0px;
        overflow-x: hidden; 
      }
      
      body {
        margin:0 0 130px;
        width:100%;
        font-weight:normal;
        font-family:Arial, sans-serif;         /* CHANGE THE FONT HERE */
        color:#219ebc;         /* CHANGE THE FONT COLOR HERE */
      }  

      /* PAGE LAYOUT */

      header, footer {
        padding:5%;
        border:0 10%;
        background-color:#8ecae6;          /* CHANGE THE HEADER AND FOOTER COLOR HERE */
        width:100%;
        margin:0px;        
      }

      footer {
        width: 100%;
        bottom: 0;
        left: 0;
        position: float;
        height:70px;
      }

      header img {
        padding-right: 10%;
        position: relative;
      }

      .wrapper {
        width:80%;
        max-width:650px;
        margin:0 auto;
        padding:30px;
      }
      
      
      /* BASIC STYLES FOR THE PAGE */
      
      a {
        color:#023047;         /* CHANGE THE LINK COLOR HERE */
        font-weight:bold;
      }

      /* Heading styles */
      h1 {
        margin:0;
        width:100%;
        font-weight:bold;
        font-family:Arial, sans-serif;          /* CHANGE THE HEADER FONT HERE */
      }

      h2, h3, h4 {
        margin:0 0 0.5em;
        padding-top: 10px;
        font-weight:normal;
      }

      /* Paragraph Text styles */
      p {
        margin:16px 0;
        line-height:1.4;
        font-weight:normal;
      }

      /* Styles for unordered lists <ul> */
      ul {
        font-family:"Courier New", Courier, monospace;
        box-shadow:0px 2px 10px #ddd;
        background-color: #ffb703;          /* CHANGE THE THINGS BACKGROUND COLOR HERE */
        border: 1px solid #555;           /* CHANGE THE THINGS BORDER HERE */
        padding:0;
        margin:2em 0 0;
        position:relative;
        z-index:200;

      }

      /* Styles for unordered list items <li> */
      ul li {
        list-style-type: none;
        border-top: 1px dotted #555; 
        font-size:14px;
        color:#000;
        height: auto;
        padding: 7px 10px 5px 25px;
        list-style-type: square;
        list-style-position: inside;
        color:#333;
      }

      .content {
        background: #8ecae6;          /* CHANGE THE INSTRUCTION BACKGROUND COLOR HERE */
      }

      .step-by-step li:before {
        background: #03071e;          /* CHANGE THE INSTRUCTION NUMBER BACKGROUND COLOR HERE */
        border-top-left-radius: 50px;          /* CHANGE THE INSTRUCTION SHAPE HERE */
        border-bottom-left-radius: 50px;
      }


      /* Object styles */
      .step-by-step img,
      .step-by-step iframe {
        width:100%;
        margin-bottom:10px;
      }

      img.logo {
        width:auto;
        height:100%;
      }


      /* ADVANCED STYLES*/

      /* Styles for the guide introduction wrapper */
      .introduction {
        padding:0px;
        position:relative;
        margin-bottom:40px;
        overflow:hidden;
        background:#fff;
      }

      hr {
        border: 0; 
        height: 0; 
        border-top: 1px solid #D3E3E8; 
      }


      ul li:first-child {
        list-style-type: none;
        border-top: none;
      }


      /* Hover state styles for list items inside unordered list <li> */
      ul li:hover {
        background-color: #eedc9c;
      }


      /* Step by step instructions */
      .step-by-step {  
        padding:0;
        position: relative;
        z-index:0;
        margin-left:40px;
      }
      .step-by-step li {
        position: relative;
        text-align: left;
        list-style-type: decimal;
        margin-bottom:20px;
      }
      .step-by-step li ol {
        margin-top:20px;
      }
      .step-by-step li li {
        list-style-type: lower-alpha;
      }
      .step-by-step .media-content {
        position:relative;
      }
      .step-by-step .media-content img {
        display:block;
        margin:0;
        width:100%;
        height:auto;
      }
      .step-by-step .media-content .caption {
        position:absolute;
        padding:0.5em 1em;
      }
      .step-by-step .media-content iframe {
        display:block;
        margin:0;
      }

      /* Content for each step */
      .content {
        padding: 20px;
        margin-bottom:10px;
        border-radius: 0px 5px 5px 5px;
        box-shadow: 0px 0px 7px 0px rgba(0,0,0,.25);           
      }       

      /* Advanced CSS for item number styling */
      .step-by-step li:before {
        content: "";
        width: 40px;
        height:80px;
        position: absolute;
        top:0;
        left:-40px;
        z-index:-1;
        background: #D3E3E8; 
        border-top-left-radius: 50px;
        border-bottom-left-radius: 50px;
      }

      /* Styles for sub-list item numbering */
      .step-by-step li li:before {
        background: #333; 
      }


      /* Footer credits */
      footer {
        margin-top:50px;
      }
      footer p {
        font-size:12px;
        color:#000;
      }

      a img {
        border:none;
      }
    </style>

  </body>
</html>
