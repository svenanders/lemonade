Lemonade
====
Lemonade is a realllly simple and flexible grid system, all you need is the knowledge of CSS/Less and basic math to use this.

Check out the live view: [here](http://joey.so/lemonade)

###Lets get started
Firstly, you'll want to link the stylesheets to your html file

```
<link rel="stylesheet" type="text/css" href="css/lemonade.css">
<link rel="stylesheet" type="text/css" href="css/styles.css">
<link rel="stylesheet" type="text/css" href="css/responsive.css">
```
###Let me run you through these sheets:
- lemonade.css is the main grid
- styles.css is your styles on top of your grid (Optional)
- responsive.css is for mobile & tablet

###Structure
Once you have your stylesheets linked, you'll want to start structuring your
.html file — lets go...

```
<div class="frame">
	<div class="bit-3">Content here</div>
	<div class="bit-3">Content here</div>
	<div class="bit-3">Content here</div>
</div>
```
###It's that easy.
So, in order to get the best results, you'll need to wrap each .bit- in a .frame class

.bit-3 is set 33.33% and will scale to 100% on mobile and tablet (Perfect for galleries)

### Support
If you have any questions or you're struggling with it, get in touch:
- [hello.joer@gmail.com](mailto:hello.joer@gmail.com)
- [@itsjoer](http://twitter.com/itsjoer)
