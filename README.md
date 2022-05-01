<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">

    <title>My page title</title>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300|Sonsie+One" rel="stylesheet" type="text/css">

    <style>
      :root {
        --base-font-color: rgb(13, 13, 13);
        --secondary-font-color: rgb(4, 5, 5);
        --emphasised-font: rgb(9, 10, 10);

        --c-background-color: rgb(34, 114, 141);
        --c-background-highlights: rgb(222, 73, 14);

        --c-yellow: rgb(181,137,  0);
        --c-orange: rgb(203, 75, 22);
        --c-red: rgb(220, 50, 47);
        --c-magenta: rgb(173, 18, 93);
        --c-violet: rgb(108,113,196);
        --c-blue: rgb(38,139,210);
        --c-cyan: rgb(42,161,152);
        --c-green: rgb(133,153,0);
      }




    body {
      background-color: var(--c-background-color);
    }  
    header {
      background-color: var(--c-background-highlights);
      color: var(--base-font-color);
      text-align:center;  
      color: var(--c-yellow);
      font-size: 150%;
      padding-top: 50px;
      
    }
    footer {
      background-color: var(--c-background-highlights);
      color: var(--base-font-color);   
    }
    main
     {
      color: var(--base-font-color)
    }

    b:hover{
      color:var(--c-orange)
    }
    a:hover{
      color:var(--c-blue)
    }

    div {
      border-style: solid;
      border-width: 3px;
      border-color: var(--c-cyan);
    } 
    .list {
      list-style: none;
      color: var(--c-magenta);
    }   
    .list {
      display: flex;
      flex-direction: row;
      justify-content: center;
      justify-content: space-between;
    }
    b {
     color: var(--c-magenta);
    }
    aside {
      color: var(--c-green);
    }
    a {
      color: var(--c-red)
    }   
    body {
      max-width: 800px;
      margin:0px;

    }
    h2, h3 {
      padding-top: 50px;
    }

    .list2 {
      position:unset;
      float: right;
    }
    .list2 {
      width: 10%
    }
    .main {
      width: 80%
    }
    .main {
      float: left
    }

    .bottom {
      float:left;
      width: 800px;
      height: auto;
    }











    </style>

  </head>

  <body >
    <!-- Here is our main header that is used across all the pages of our website -->

    <header class="top">
      <h1>Header</h1>
    </header>

    <nav class="top">
      
      <ul class="list" >
        <li><b href="#">Home</b></li>
        <li><b href="#">Our team</b></li>
        <li><b href="#">Projects</b></li>
        <li><b href="#">Contact</b></li>
      </ul>
      

       <!-- A Search form is another common non-linear way to navigate through a website. -->

       <form>
         <input type="search" name="q" placeholder="Search query">
         <input type="submit" value="Go!">
       </form>
     </nav>

    <!-- Here is our page's main content -->
    <main>

      <!-- It contains an article -->
      <article class="main">
        <h2>Article heading </h2>

        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Donec a diam lectus. Set sit amet ipsum mauris. Maecenas congue ligula as quam viverra nec consectetur ant hendrerit. Donec et mollis dolor. Praesent et diam eget libero egestas mattis sit amet vitae augue. Nam tincidunt congue enim, ut porta lorem lacinia consectetur.</p>

        <div>
        <h3>Subsection </h3>

        <p id="article1">Donec ut librero sed accu vehicula ultricies a non tortor. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean ut gravida lorem. Ut turpis felis, pulvinar a semper sed, adipiscing id dolor.</p>
        
        <p id="article1">Pelientesque auctor nisi id magna consequat sagittis. Curabitur dapibus, enim sit amet elit pharetra tincidunt feugiat nist imperdiet. Ut convallis libero in urna ultrices accumsan. Donec sed odio eros.</p>
        </div>
        
        <div>
        <h3>Another subsection</h3>

        <p id="article1">Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus. Cum soclis natoque penatibus et manis dis parturient montes, nascetur ridiculus mus. In rutrum accumsan ultricies. Mauris vitae nisi at sem facilisis semper ac in est.</p>

        <p id="article1">Vivamus fermentum semper porta. Nunc diam velit, adipscing ut tristique vitae sagittis vel odio. Maecenas convallis ullamcorper ultricied. Curabitur ornare, ligula semper consectetur sagittis, nisi diam iaculis velit, is fringille sem nunc vet mi.</p>
        </div>
      </article>

      <!-- the aside content can also be nested within the main content -->
      <aside>
        <h2>Related</h2>

        <ul class="list2">
          <li><a href="#">Oh I do like to be beside the seaside</a></li>
          <li><a href="#">Oh I do like to be beside the sea</a></li>
          <li><a href="#">Although in the North of England</a></li>
          <li><a href="#">It never stops raining</a></li>
          <li><a href="#">Oh well...</a></li>
        </ul>
      </aside>

    </main>

    <!-- And here is our main footer that is used across all the pages of our website -->

    <footer class="bottom">
      <p>©Copyright 2050 by nobody. All rights reversed.</p>
    </footer>



  </body>
</html>