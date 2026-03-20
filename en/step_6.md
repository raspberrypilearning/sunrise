## Animating the sky

Animation isn't just for movement. Let's animate the sky to turn dark at night.

+ Add an animation called `sky` to your `style.css` file:

    --- code ---
    ---
    language: css
    line_numbers: false
    ---
    @keyframes sky {
        0% { background: black; }
        100% { background: lightblue; }
    }
    --- /code ---

    Notice that this time you're animating the colour of the sky, and not the position.

+ Add code to your sky, to tell it to use your new animation:

    --- code ---
    ---
    language: css
    line_numbers: false
    ---
    animation: sky 10s;
    --- /code ---

    ![screenshot](images/sunrise-sky.png)

+ Click **Autorun** to test your animation. 
