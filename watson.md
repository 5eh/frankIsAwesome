# This is Watson's cooler marketdown file
## how's it going?

lol this is absolutely fantastic news, no # = jut paragraph and text
- haha remarketable 
- this is truly epic
- this is insanery
1. how's it going?
2. the name's watson?
3. I think Frank can slowly type faster than me

[How's it going?] (https://pictureofwatsonscat.com/)

### Watson's dog
Watson's dog is not ~~yellow~~, but light and brown :sunglasses:

```js
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title></title>
  </head>
  
  <body>
    <style>
      h1 {
        text-align: center;
        font-size: 100px;
        color: #333;
      }
      p {
        text-align: center;
        color: #333;
        font-style: italic;
      }
    </style>

    <h1>GIVE ME 5001</h1>
    <p>or click this butoon 2000times</p>
    <div style="display: flex; padding: 30px">
      <button
        id="cryptoMe"
        style="
          flex: 1 1 auto;
          border-radius: 5px;
          font-stretch: 100%;
          font-family: 'Courier New', Courier, monospace;
          font-size: large;
        "
      >
        Crypto Me 500$
      </button>
      <button
        id="clickMe"
        style="
          flex: 2 1 auto;
          margin-left: 25px;
          border-radius: 5px;
          font-family: 'Courier New', Courier, monospace;
          font-size: large;
        "
      >
        Click this button 5000times
      </button>

      <h2></h2>
      <script>
        const buttonCryptoMe = document.getElementById("cryptoMe");
        const buttonClickMe = document.getElementById("clickMe");

        buttonCryptoMe.addEventListener("click", () => {
          console.log("Hello");
        });

        buttonClickMe.addEventListener("click", function asdf() {
          console.log("+1");
          addingStuff();
        });

        function addingStuff() {
          const newDiv = document.createElement("div");

          // and give it some content
          const newContent = document.createTextNode("Hi there and greetings!");

          // add the text node to the newly created div
          newDiv.appendChild(newContent);

          // add the newly created element and its content into the DOM
          const currentDiv = document.getElementById("div1");
          document.body.insertBefore(newDiv, currentDiv);
        }
      </script>
    </div>
  </body>
</html>

```

## Commands that we used today?
1. mkdir {} - make directory 
2. cd {} - open directory 
3. git -clone {} - clone repo link
4. dir - see new folder 
5. cd {} - open repo 
-- 
6. echo {name} > {file_type} 
* [echo = console.log() for the terminal]
* [type {} = Views text of file] 
* [notepad {} = opens notepad file]
7. del {} = deletes file
8. git add {} = add file to git
9. git status = check commits
10. git commit -m {} = commits and adds log 
11. git status
12. git push = uploads to cloud
13. git log (--oneline) = view history of dir