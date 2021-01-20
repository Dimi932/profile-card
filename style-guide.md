# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Dark cyan: hsl(185, 75%, 39%)
Very dark desaturated blue: hsl(229, 23%, 23%)
Dark grayish blue: hsl(227, 10%, 46%)

### Neutral

Dark gray: hsl(0, 0%, 59%)

## Typography

### Body Copy

- Font size (name and stats): 18px

### Font

- Family: [Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans)
- Weights: 400, 700


.box{
  width: 100%;
  min-height: 100vh;
  background-color: hsl(185, 75%, 39%);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-image: url(images/bg-pattern-top.svg),
    url(images/bg-pattern-bottom.svg);
 background-repeat: no-repeat, no-repeat;
 background-position: right 52vw bottom 38vh, left 49vw top 51vh;
 padding: 20%;
}
.top-box {
  position: relative;
  min-width: 100%;
  height: 200px;
  background-image: url(images/bg-pattern-card.svg);
  border-top-left-radius: 8px;
  border-top-right-radius: 8px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

}
.middle-box {
background-color: white;
min-width: 100%;
overflow: hidden;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;

}
img {
  border-radius: 50%;
  margin-bottom: 30px;
  position: absolute;
  top: 145px;
  border-style: solid;
  border-width: 5px;
  border-color: white;
  display: flex;
  justify-content: center;
  margin: 0 auto;
}

h3 {
  margin-top: 16px;
  margin-bottom: 25px;
  opacity: 0.5;
  font-weight: normal;
  color: hsl(227, 10%, 46%);
}

h1 {
  text-align: center;
  font-size: 18px;
  margin-top: 50px;
  color: hsl(229, 23%, 23%);
}

p {
  text-align: center;
  opacity: 0.5;
  margin-top: 10px;
  color: hsl(227, 10%, 46%);
}


span {
  margin-left: 16px;
  opacity: 0.5;
  font-weight: lighter;
  color: hsl(227, 10%, 46%);
}


.bottom-box {
  background-color: white;
  min-width: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  border-bottom-left-radius: 8px;
  border-bottom-right-radius: 8px;
  padding: 20px;
  border-top: solid;
  border-color: #e8eae6;

}

.social-media1, .social-media2, .social-media3 {
  width: 20%;

}

.stats {
  margin-top: 10px;
}


.attribution {
  font-size: 11px; text-align: center;
  margin-top: 50px;
}

.attribution a { color: hsl(228, 45%, 44%); }

@media (max-width: 768px) {

  .box {
    padding: 8px;
  }
  .bottom-box {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

}
