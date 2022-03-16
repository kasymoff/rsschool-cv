# Ulukbek Kasymov
- GitHub: @kasymoff 
- Telegram: @UlikKas 
- Discord: @Fakie
## About me:
### I am a self-taught programmer. I like to create web-apps and web-sites. I have a passion for programming and I am always trying to improve my skills. Also like to work with the latest technologies and I am always trying to learn new things. My goal is to become a full-stack developer.
## Skills:
- HTML5
- CSS3
- JavaScript
- GIT

## Code examples:
```
function center (strng, width, fill = ' ') {
  if (strng.length >= width) {
    return strng;
  } else {
    const remainFill = width - strng.length;
    const leftSide = Math.ceil(remainFill/2);
    const rightSide = Math.floor(remainFill/2);
    const leftArr = new Array(leftSide);
    const rightArr = new Array(rightSide);
    leftArr.fill(fill);
    rightArr.fill(fill);
    const leftStr = leftArr.join('');
    const rightStr = rightArr.join('');
    return [leftStr, strng, rightStr].join('')
  }
}
```
