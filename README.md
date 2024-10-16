# BoilerPlate
The standard boilerplates of HTML, CSS and Js <br>
Fork or Clone this repo and start crafting your websites
## How to stick footer at the bottom of the page?
Create a div.wrapper and keep everything inside it except the footer part. <br>
Then, in CSS, just add the following code:
```
body{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
```
