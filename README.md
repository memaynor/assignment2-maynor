# Max Maynor
### Football
Football is a team sport that is fun to watch with the family and friends. It is cool seeing the QB have to react in the moment.

---

### Favorite Team
#### Chiefs
1. Patrick Mahomes
2. Travis Kelce
3. JuJu
- Cowboys 
- Titans
- Dolphins

[AboutMe](AboutMe.md)

---

### Table
This table is a few countries I recommend people visit
| Name | Reason to visit | Days I would spend |
| --- | --- | ---: |
| Ireland | Very beautiful land and cool architecture plus good food | At least a week, probably more |
| Japan | Cool atmosphere | A week |
| Italy | Architecture and food | A month at least |
| Australia | I just thinks its cool | A week ish |

---

### Quotes
> "(...)normalcy is an illusion. Each person is utterly unique. A standard of normalcy is something that most people of the world simply will never access." *Colleen Houck*
>
> "For God so loved the world that He gave his one and only Son, that whoever believes in Him shall not perish but have eternal life." *John the Apostle*

---

> [CSS Checkbox Input Styling](https://stackoverflow.com/questions/1120879/css-checkbox-input-styling)

```
/*
  Hide the original radios and checkboxes
  (but still accessible)

  :not(#foo) > is a rule filter to block browsers
  that don't support that selector from
  applying rules they shouldn't

*/
li:not(#foo) > fieldset > div > span > input[type='radio'],
li:not(#foo) > fieldset > div > span > input[type='checkbox'] {
  /* Hide the input, but have it still be clickable */
  opacity: 0;

  float: left;
  width: 18px;
}


li:not(#foo) > fieldset > div > span > input[type='radio'] + label,
li:not(#foo) > fieldset > div > span > input[type='checkbox'] + label {
  margin: 0;
  clear: none;

  /* Left padding makes room for image */
  padding: 5px 0 4px 24px;

  /* Make look clickable because they are */
  cursor: pointer;

  background: url(off.png) left center no-repeat;
}

/* Change from unchecked to checked graphic */
li:not(#foo) > fieldset > div > span > input[type='radio']:checked + label {
  background-image: url(radio.png);
}
li:not(#foo) > fieldset > div > span > input[type='checkbox']:checked + label {
  background-image: url(check.png);
}
```
<https://css-tricks.com/snippets/css/custom-checkboxes-and-radio-buttons/>
