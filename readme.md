# Sticky elements
## Combined with border-radius container
### Solutions for safari:
- Apply `transform: translateZ(0);` on the container element
- Apply `-webkit-mask-image: -webkit-radial-gradient(white, black);` on the container element

# Flexible <Table> in fixed flexbox width combined with `overflow: scroll` on the table
In some situations you have a fixed content, meaning some of the sizes are fixed some are 
flexible. If you want to have a table element inside there it may happen that the scaling of you layout goes wrong
- Add `margin-right: -9999px;` on the table element
