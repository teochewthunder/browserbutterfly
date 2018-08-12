# Browser Butterfly

This widget's appearance is written in HTML, and is derived from four shaped divs with elliptical fill. The flapping motion is via a named animation in CSS.

JavaScript wil randomize certain attributes of the butterfly, such as **size**, **rotation**, **position** and **flapping speed**.

The first three attributes are achieved by modifying the butterfly's "wrapper". In particular, all divs inside the "wrapper" are sized relatively to the wrapper, so modifying the height and width of the "wrapper" will scale the butterfly nicely.

The ,ain JavaScript function is *flutter()*, which will recursively call itself via the *setTimeout()* callback at the end, so that a new set of randomized attributes now apply to the butterfly, causng it to look like it's fluttering around the screen and moving nearer/further away from the user.
