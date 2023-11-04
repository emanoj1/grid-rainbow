# Create Rainbow circle using Grid

### When did you start learning it?
Saturday, 04 November 2023

### What is a CSS Grid Layout in CSS?
It's a system which uses rows and columns to layout web elements. It's supposed to make designing easier.

### How does it work?
It makes use of a parent and child elements. There's only 1 parent but may child elements (_as I understand as of today_)

It's triggered when using this display property:
```display:grid```

### Explain in brief how the rainbow was created.
The first step is to create a ```<div></div>``` for 3 primary colours - orange, green, purple.

``````
<body>
    <div id="one"></div>
    <div class="two"></div>
    <div class="three"></div>

</body>
``````
Then assign a:
-  thick border of red for the orange
- thick border of yellow for the green
- thick border of blue for the purple