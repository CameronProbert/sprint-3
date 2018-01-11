What happens to the layout when you resize the screen to less than 550 px. 
The page changes from using a grid layout to a vertical scrolling layout.

How do you think that works?
The <550px layout is actually the default layout. The change is due to this code:

* Bigger than 550 */
@media (min-width: 550px) {
  ...
  }
}

There are also two more @media lines that change the layout again for when the width is larger than 750 and 1000.