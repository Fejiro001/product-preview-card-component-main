### Structure
- body
    - div(role: card)--flex(desktop: row & mobile: column)
        - div(role: image-container)
            - img
        - div(role: info)
            - h1
            - h2
            - p
            - h3 > span
            - button


### Things to note
- change image for when its desktop or mobile using media queries
- cross-out price - text-decoration: line-through;
- the 2 divs side by side - https://www.geeksforgeeks.org/how-to-place-two-div-side-by-side-of-the-same-height-using-css/
- active state button - https://www.w3schools.com/cssref/sel_active.php
- add icon next to text in button - https://stackoverflow.com/a/49997979
- accessibility
    - adding role to non-semantic tags