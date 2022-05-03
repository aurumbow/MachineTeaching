I feel like I say this about every project, but I really would have liked to spend more time and focus on this. Obviously I would have loved to have infinite time to troubleshoot the bug that prevented the original Unity concept from launching and develop it to a final presentable state, but I also would have liked to spend more time finding ways to have Machine Teaching's output be a proper JSON file that is remembered by the program itself in addition to the output and to give the user more variety in their input options because as it stands the traits are all strings or boolean variables. These files are really human-legible, which adds to the theme that ML algorithms are just using data that is given to them by humans, but it would have been nice to push the project a bit to find ways to incorporate other variable types. 

The main crux of the practical implementation of the project was built off of combining things I learned this year - largely the specifics of javascript objects and how they behave - with things I already knew, like combining javascript with HTML and using the external library jQuery to pass things between them instead of having a different method for every unique button. I am not exempt from reliance on external programming tools! I made sure jQuery worked with Github pages before I did so, but I used jQuery for most of the methods to grab the name of the button and save it as a string property of the object. 
````
 function setColor(){
     thisThing.color = $(event.target).text().trim();
     console.log($(event.target).text().trim());
    }
````
jQuery code is indicated by the $ symbol before a method call. If I were to attempt the same code without jQuery it would have looked more like the code used to set the objects boolean traits, which are jQuery free: 
````
function setAliveTrue(){
      thisThing.isAlive = true;
      console.log("true");
    }
````
Even though I did not learn many new practical skills beyond integrating the different coding components together and the syntax used to do some of the specific tasks of this project such as file downloading, I still think that working on this really helped me rethink the ways I approach a programming project and the ways I think about mine and other people's code. 
