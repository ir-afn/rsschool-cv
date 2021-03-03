## Irina Afonina
contact: @irr2irr (Telegram)

### About me
I want to become a frontend developer. Currently working as a content manager. 
My strong points:
* attention to detail
* English (C2)
* friendliness

### My skills
Currently learning HTML, CSS and JS
Some of my code:
```
const isBracketStructureBalanced = (string) => {
  const stack = [];
  let openingIndex;
  let closingIndex;
  for (const item of string) {
    if (openingSymbols.includes(item)) {
      stack.push(item);
    } else if (closingSymbols.includes(item)) {
      closingIndex = closingSymbols.indexOf(item);
      openingIndex = openingSymbols.indexOf(stack.pop());
      if (openingIndex !== closingIndex) {
        return false;
      }
    }
  }
  return stack.length === 0;
};
```


