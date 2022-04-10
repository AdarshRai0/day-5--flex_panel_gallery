## Flex Panel Gallery
*******

![22](https://user-images.githubusercontent.com/91651054/162606464-0c326d5b-4503-4a8e-a992-62afdc75044c.png)


*******

What I learned on this mini-project.

*******

### toggle

You can toggle a class with the following code. This will respond to an event via an event listener. This is commonly used in click events (which is what its used for in this case).

``` javascript
this.classList.toggle('open');
```

- `this` refers to each separate panel when clicked on

### event.propertyName

When listening for `transitionend`, the event might return multiple results. Utilising `propertyName` you can respond to a transition of choice.

``` javascript
event.propertyName.includes('flex');
```

- `includes()` - Used here, since IE explorer refers to the flex property as `flex-grow`

### Tasks

- [ ] Complete [What the Flexbox](https://flexbox.io/)
