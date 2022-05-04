# Thats Franks Markdown File
![Brave](https://img.shields.io/badge/Brave-FB542B?style=for-the-badge&logo=Brave&logoColor=white)

## Franks Cat

### Franks Cat Head
Franks Cat has a Head and this head is **blue**

### Franks Cat Body
Franks Cat has a Body and this body is **yellow**

### Frank Cat Arm
Franks Cat has some Arms and these arms are **green**

## Franks Dog

Franks dog is ~~yellow~~

## Why is markdown used?

Markdown is used to write nice formatted Text and has heavy use in the IT Indurstry. Its easier then writing html, for example.

## How to make a codeblock?

```js
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
```

## Commands that we used today?

### Windows Shell Commands
```sh
mkdir Watson
```
It creates a directory, named Watson

```sh
cd Watson
```
it changes directory to Watson

```sh
dir .
```
shows whats in the current directory

```sh
echo "Watson"
```
Prints Watson to the console

```sh
echo "Watson" > watson.md
```
Creates a markdown Files, called watson.md with the content of "watson"

### Git commands 

....
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
...

### Adding pictures&links in markdown
Thats a picture in markdown, not scaleable as  i know
![Thats a awesome picture](https://i.ibb.co/H7PWPtR/IMG-9144.jpg)

You always can use html tags, like img, if you need more controll, but thats not markdown, but 90 of every markdown file gets compiled to `html`
<img src="https://i.ibb.co/H7PWPtR/IMG-9144.jpg" alt="Thats a smaller awesome picture" style="width: 100px"></img>

[Thats just an link](https://i.ibb.co/H7PWPtR/IMG-9144.jpg)

### Lets write with mini codeblocks

Hola Watson,

type in your console `pandoc -f markdown -t html frank.md -o frank.html` to convert it to simple html.

Best Regards
**Frank**

### Tables in Markdown

|Syntax|Description                                    |
|:------------------:|-----------:|
|git --help        | shows git help|
|git log --oneline | shows past git commit quite nicely|
|dir | shows whats in the current folder|


Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.