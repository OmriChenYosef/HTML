# In this seection we will learn
## Combing selector
### For example we want for a some reason to style pararph for red color but if the paragrph in a box we want color yellow there is a conflict, to solve that we cant user class name but it happen a lot so there is more way to do that.

#### index.html
`<div class = "some-name">`<br />
`<p> some content </p>`<br />
`</div>`


#### style.css
p{
    color: red;
}

.some-name p{
     color: yellow;
}