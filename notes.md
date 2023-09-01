### Structure

> body

    >> div(role: card)--flex(desktop: row & mobile: column)

        > - div(role: image-container)
            > - img
            
        > - div(role: info)
            > - h1
            > - h2
            > - p
            > - h3 > span
            > - button > icon > p


### Things to note
- change image for when its desktop or mobile using media queries
- cross-out price - text-decoration: line-through;
- the 2 divs will have `flex: 50%`
- active state button - https://www.w3schools.com/cssref/sel_active.php
