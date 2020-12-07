# -web-homepage-
Homepage
!DOCTYPE html>

<html lang="en">
    <head>
    <meta charset=="UTF-8" />
    <title>First Webpage </title>
     <script>
            function greet()
            {
              let name = document.querySelector('#name').value;
              if (name == '')
               {
                  name = 'Welcome to my first webpage, this will give a little background about myself, my favortie, food, my favorite genres of music, and my goals for the future.';
                   
               }
                document.querySelector('#result').innerHTML =  'Hello, ' + name + '!'              
            } 
        </script>
    <link rel="stylesheet" href="https://volodymyrkushnir.com/assets/stylesheets/base.css">
   </head>
    <body style="font-family:cursive">
       
         <form onsubmit="greet(); return false;">
            <input type="text" id="name">
            <input type="submit">
        </form>
        <div id= "result">
        Hello!
        </div>
        
        <select>
            <option value="Background">Background</option>
             <option value="initial" selected>Favorite Food</option>
             <option value="Favorite Music">Favorite Music</option>
        </select>
    <script>
        document.querySelector('select').onchange = function() {
            document.querySelector('p').style.fontSize = this.value;
        }
        </script>    
      <main>
      <article>
        <div class="page" style="border-color: midnightblue;">
          <div class="stackable grid">
            <div class="row">
              <div class="three wide center aligned column">
                <!-- Avatar -->
              </div>
              <div class="thirteen wide column">
                <div class="stackable grid">
                  <div class="sixteen wide column">
    <h1>Tina Dennis</h1>
    
        <h2>Background</h2>
                     
        <p>
        My name is Tina Dennis and I have no middle name, I was born in a small country in west Africa called Liberia <<li><a href="https://www.cia.gov/library/publications/the-world-factbook/geos/li.html">Website</a></li> . Liberia is a very small country and is sometimes reffered to as the stepchild of America. I immigrated to the United States when I was only 6 years old and did not know a spic of english. I was placed in ESL for 3 years to learn english and I had a blast because I made so many new friends and had alot of fun in that class. I enjoyed learning and going to school as a child and I was so happy just to be there. I grade really began to improve in fourth grade because I could actually understand what the teacher was tecahing me.I moved to North Carolina in 2010 when I was 12 and that was a huge change for me becuase I did not know anybody there besides a few family members. Fortunately I moved back to Philadelphia 3 years later. I graduated high school in 2017 and I took a year off of school to join the U.S Army so the army could help me pay for college. After my army training which consisted of basic combat trainign and advanced individual training I applied to Shippensburg University which is located in Shippensburg, PA. I did not like the school because it was basically located in the middle of nowhere and I was tired of driving 2-3 hours to come home to drill and to see my family. So when the corona virus pandemic started I decided it would be best for me to move back home, and I  transferred to Temple university for the Computer Science program. 
        </p>
        <h3>Favorite Food</h3>
        <p>
            <link href="http://fonts.googleapis.com/css?family=Corben:bold" rel="stylesheet" type="text/css">
           My Favorite foods consist of Jollof rice, Fufu and soup, fruits and vegitables, and sushi. I like to try foods from all over the world and experience as much culture as i can.
            <img src= "Jollof_rice.jpeg" atl="Picture of Jollof Rice">
            <img src= "Vegetable_gimbap.jpeg" atl="Picture of Jollof Rice">
             <img src= "Culinary_fruit_font_view.jpeg" atl="Picture of Jollof Rice">
             <img src= "Fufu.jpeg" atl="Picture of Jollof Rice">
                
         </p>          
        <h4>Favorite Genre of Music</h4>
        
          <style>
            table
            {
                border: 20px solid grey;
                border-collapse: collapse;
            }
            td
            {
                border: 9px solid black;
                padding: 60px;
            
            }
        
            .header
            {
                background-color:aliceblue;
            }
        
        </style>
   </head>
    <body>
        <table>
            <tr class="header">
                <td>Country</td>
                <td>Jazz</td>
                <td>Hip-Hop</td>
            </tr>
        <tr   class="header">
                <td>Rock</td>
                <td>Afro-beats</td>
                <td>R and B</td>
            </tr>
        <tr class="header">
                <td>Latin Pop</td>
                <td>Reggae</td>
                <td>Blues</td>
            </tr>
            
        
        </table>
 
    </body>
</html>
