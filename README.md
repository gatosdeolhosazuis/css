# css
## erro 1
https://westonganger.com/posts/cannot-click-html-link-after-using-css-float
```
.your-link{
  float: right;
  position: relative; // can be either relative, absolute, or fixed 
  z-index: 10; // this fixes it but requires one of the above positions
}
```
