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