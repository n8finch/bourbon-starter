##Boubon Starter##

My setup for prototypeing with Bourbon, Neat, Bitters, and Refills.

```
npm update
bower update
```

---

create in the project root directory a folder "sass" with a file "style.scss". All of your partials will go in here.

Run this in the project root directory: 
`sass --watch sass/style.scss:style.css`

`sass --watch [sass file]:[output file`


Install bourbon and Neat: 
```
cd sass
bourbon install
neat install
bitters install
```

Normalize before bitters
https://cdnjs.com/libraries/normalize