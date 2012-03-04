title: impress.js | presentation tool based on the power of CSS3 transforms and transitions in modern browsers
author: Bartek Szopka


%%%%%
%% Add some inline style rules...

%css

a {
  color: inherit;
  text-decoration: none;
}

body {
  background-image: -webkit-linear-gradient(top left, silver, white);
  background-image:    -moz-linear-gradient(top left, silver, white);
  background-image:     -ms-linear-gradient(top left, silver, white);
  background-image:      -o-linear-gradient(top left, silver, white);
  background-image:         linear-gradient(top left, silver, white);
}

.step {
  width: 700px;
  height: 400px;
  padding: 40px 60px;

  font-size: 48px;
  text-align: center;

  opacity: 0.3;
}

.step.active {
  opacity: 1;
}

.slide {
  background: white;
}

code {
  background-color: yellow;
  font-size: 14px;
}

%end


%%%%%%%%%%%%%%%%%%%
%% Here we go...


!SLIDE slide x=-1000 y=-1500

Aren't you just **bored** with all those slides-based presentations?
`x=-1000 y=-1500`

!SLIDE slide x=0 y=-1500

Don't you think that presentations given **in modern browsers**
shouldn't **copy the limits** of 'classic' slide decks?
`x=0 y=-1500`

!SLIDE slide x=1000 y=-1500

Would you like to **impress your audience** with **stunning visualization** of your talk?
`x=1000 y=-1500`

!SLIDE x=0 y=0 scale=4

then you should try  
impress.js<sup>*</sup>  
<sup>*</sup>no rhyme intended
`x=0 y=0 scale=4`

!SLIDE x=850 y=3000 rotate=90 scale=5

It's a **presentation tool**  
inspired by the idea behind [prezi.com](http://prezi.com)  
and based on the **power of CSS3 transforms and transitions** in modern browsers.
`x=850 y=3000 rotate=90 scale=5`

!SLIDE x=3500 y=2100 rotate=180 scale=6

visualize your **big** thoughts
`x=3500 y=2100 rotate=180 scale=6`

!SLIDE x=2825 y=2325 z=-3000 rotate=300 scale=1

and **tiny** ideas
`x=2825 y=2325 z=-3000 rotate=300 scale=1`

!SLIDE x=3500 y=-850 rotate=270 scale=6

by **positioning**, **rotating** and **scaling** them on an infinite canvas
`x=3500 y=-850 rotate=270 scale=6`

!SLIDE x=6700 y=-300 scale=6

the only **limit** is your **imagination**
`x=6700 y=-300 scale=6`

!SLIDE x=6300 y=2000 rotate=20 scale=4

want to know more?
[use the source](http://github.com/bartaz/impress.js), Luke!
`x=6300 y=2000 rotate=20 scale=4`

!SLIDE x=6000 y=4000 scale=2

one more thing...
`x=6000 y=4000 scale=2`

!SLIDE x=6200 y=4300 z=-100 rotate-x=-40 rotate-y=10 scale=2

have you noticed it's in 3D<sup>*</sup>?  
<sup>*</sup>beat that, prezi ;)
`x=6200 y=4300 z=-100 rotate-x=-40 rotate-y=10 scale=2`

!SLIDE x=3000 y=1500 scale=10

`x=3000 y=1500 scale=10`

%% The End
%%%%%%%%%%%%%%%