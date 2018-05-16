# Chapter 3: Flex Container

## Creating A Flex Container

## Flex Flow

```html
<div class="container">
  <div class="item">Flex Item 1</div>
  <div class="item">Flex Item 2</div>
  <div class="item">Flex Item 3</div> 
</div>
```

```css
.container {
  display: flex;
  border: 2px solid black;
  flex: 1;
}

.item {
  display: flex;
  justify-content: center;
  align-items: center;
  border: 2px solid black;
  height: 10rem;
  width: 10rem;
  margin: .5rem;
  color: white;
  background-color: blue;
}
```
![3-1 flex-direction: row](img/3-1-direction-row.png)

```css {
  .item {
    flex-direction: column;
  }
}
```

![3-2 flex-direction: column](img/3-2-direction-column.png)

## Display Order

```html
<div class="container">
  <div class="item" style="order: 1;">Flex Item 1</div>
  <div class="item">Flex Item 2</div>
  <div class="item">Flex Item 3</div> 
</div>
```
![3-3 order](img/3-3-order.png)

## Flexibility

### Flex Grow

```html
<div class="container">
  <div class="item">Flex Item 1</div>
  <div class="item">Flex Item 2</div>
  <div class="item" style="flex-grow: 1;">Flex Item 3</div>
</div>
```

![3-4 flex-grow](img/3-4-flex-grow.png)
```html
<div class="container">
  <div class="item" style="flex-grow: 1;">Flex Item 1</div>
  <div class="item">Flex Item 2</div>
  <div class="item" style="flex-grow: 1;">Flex Item 3</div>
</div>
```

![3-5 flex-grow](img/3-5-flex-grow-2.png)

```html
<div class="container">
  <div class="item" style="flex-grow: 1;">Flex Item 1</div>
  <div class="item">Flex Item 2</div>
  <div class="item" style="flex-grow: 2;">Flex Item 3</div>
</div>
```

![3-6 flex-grow](img/3-6-flex-grow-3.png)

### Flex Shrink

### Flex Basis

### Shorthand

## Alignment

### Justify Content

### Align Items

### Align Content