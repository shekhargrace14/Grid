# Grid


conatiner

gap
grid-template-columns - to define with of child
grid-template-rows - to define height of child
justify-content
align-content
align-items


Grid Child Items

justify-self
align-self
grid-column
grid-row
grid-area


Grid template areas

.grid-container{
    grid-template-areas:
        "header header header header header header"
        "menu main main main right right"
        "menu footer footer footer footer footer"
}

.item1{
    grid-area:header;
}
.item2{
    grid-area:menu;
}
.item3{
    grid-area:main;
}
.item4{
    grid-area:right;
}
.item5{
    grid-area:footer;
}

















.container{
    /* border: 2px solid red; */
    display: grid;
    width: 80%;
    margin: 5% auto;
    
/* ----------------------------------------------------------------------------------------------- */
    /* #grid-gap = gap = (row-gap + column-gap) */
    /* grid-gap: 20px; */
    gap: 20px;

    /* row-gap: 20px; */
    /* column-gap: 20px; */

/* ---------------------------------------------------------------------------------------------- */
    /* grid-template-columns helps to define the width of the columns */

    /* grid-template-columns: 100px 200px 300px; */
    /* grid-template-columns: 50% 30vw 1fr; */
 
    /* ------------------------------------ */
    /* fr= fraction */
    /* grid-template-columns: 1fr;  */
    /* grid-template-columns: 1fr 1fr 1fr 1fr; */
    
    /* short code  */
    /* grid-template-columns: repeat(4, 1fr); */
    /* grid-template-columns: auto 200px auto; */

    /* grid-auto-columns: 500px; */

    /* this line of code will remove all media query and responsive code */
    /* grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)) */


/* ------------------------------------------------------------------------------------------------ */

    /* grid-template-rows helps to define the height of the rows */

    /* grid-template-rows: 200px 80px 200px; */
    /* grid-template-rows: 1fr 3fr 4fr 2fr; */

    /* rest of the rows height will be define by this property */

    grid-auto-rows: 100px;
    /* grid-auto-rows: minmax(auto,auto); */
    /* grid-auto-rows: minmax(100px,200px); */
    /* grid-auto-rows: minmax(300px,auto); */
    /* grid-auto-rows: minmax(auto, 300px); */

    /* justify-content: center; */
    /* justify-content: end; */
    /* justify-content: space-around; and other values of jc  */

    /* align-content: ; is different from align-items: ; */

    /* align-content: center; */

    /* align-items: center ; */

}

/* #item-*{ */
    /* justify-content: stretch; default  */
    /* justify-self: center; */
    
    /* align-self: start; */
    /* align-self: end; */
    /* align-self: center; */

    /* grid-column-start: 2 ; */
    /* grid-column-end: 3  ; */
    /* grid-column:  1/2; shorthand of grid-column-start-end: ; */
    /* grid-column: 1 / span 2; */
    /* grid-column: 1/ -1; */

    /* grid-row-start: 2 ; */
    /* grid-row-end: 3; */
    /* grid-row:  1/2; shorthand of grid-row-start-end: ; */
    /* grid-row: 1 / span 2; */
    /* grid-row: 1/ -1; */

    /* grid-area: 1/ -1; shorthand of  grid-column and grid-row */
    /* grid-area: 1/2/3/3; */
/* } */