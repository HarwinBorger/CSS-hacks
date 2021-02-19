# Sticky elements

## Combined with border-radius container

### Solutions for safari:

- Apply `transform: translateZ(0);` on the container element
- Apply `-webkit-mask-image: -webkit-radial-gradient(white, black);` on the container element


# Flexbox

## Flexible `<Table>` in fixed flexbox width combined with `overflow: scroll` on the table
  

In some situations you have a fixed content, meaning some of the sizes are fixed some are 
flexible. If you want to have a table element inside there it may happen that the scaling of your layout goes wrong

- Add `margin-right: -9999px;` on the table element

# Video's
Fix gray backgrounds on mobile browsers, occurs in mp4 video's with either a black or white background

```
video {
  filter: brightness(100%); // fix gray backgrounds on mobile browsers, occurs in video's with either a black or white background
}
```
