%%
%% Sample based on the blog story by Andi Smith titled 'Impress at Presentations with Impress.js'
%% -> http://www.andismith.com/blog/2012/01/impress-with-impress


%%%%%
%% Add some inline style rules...

%css

.step {
  width: 500px;
  height: 400px;
  padding: 40px 60px;
  font-size: 48px;
  text-align: center;

  opacity: 0.3;
  border-radius: 10px;
  border: 2px solid blue;
}

.step.active {
  opacity: 1;
  border: 3px solid red;
}

code {
  background-color: yellow;
  font-size: 14px;
}

%end



%%%%%%%%%%%%%%%%%%%
%% Here we go...

!SLIDE

Slide One


!SLIDE y=600

Slide Two `y=600`


!SLIDE x=1200 y=600 rotate=180

Slide Three `x=1200 y=600 rotate=180`


!SLIDE x=1200 scale=0.5

Slide Four `x=1200 scale=0.5`


!SLIDE x=600 y=300 scale=2

Overview `x=600 y=300 scale=2`