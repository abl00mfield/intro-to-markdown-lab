# CSS Selector Anatomy

![computer screen with code](./assets/mohammad-rahmani-oXlXu2qukGE-unsplash.jpg)

CSS Selectors are used to style HTML elements. Knowing how to use them is essential for writing CSS code.

## Basic Structure of a CSS Selector

A CSS selector consists of different components that define which HTML elements should be targeted and how they should be styled.

```css
selector {
  property: value;
}
```

### 1. **Selector**

The selector specifies the HTML element(s) that should be styled.

```css
h1 {
  color: red;
}
```

_Targets all `<h1>` elements and applies the color red._

### 2. **Declaration Block**

The declaration block is enclosed in curly braces `{}` and contains one or more declarations.

```css
p {
  font-size: 18px;
  text-align: center;
}
```

_Targets `<p>` elements and applies multiple styles._

### 3. **Property**

A property defines the aspect of an element that should be styled.

```css
input {
  background-color: grey;
}
```

_`background-color` is the property that sets the background color of the button._

### 4. **Value**

A value is assigned to a property to define its appearance.

```css
a {
  text-decoration: none;
}
```

_`none` is the value assigned to `text-decoration` to remove underlines from links._

## Types of CSS Selectors

1. **Universal Selector (`*`)**

   ```css
   * {
     margin: 0;
     padding: 0;
   }
   ```

   _Selects all elements in the document._

2. **Element Selector**

   ```css
   h1 {
     font-weight: bold;
   }
   ```

   _Selects all `<h1>` elements._

3. **Class Selector (`.`)**

   ```css
   .button {
     background-color: blue;
   }
   ```

   _Selects all elements with class `button`._

4. **ID Selector (`#`)**

   ```css
   #header {
     font-size: 20px;
   }
   ```

   _Selects the element with the ID `header`._

5. **Attribute Selector**

   ```css
   input[type="text"] {
     border: 1px solid black;
   }
   ```

   _Selects `<input>` elements with `type="text"`._

6. **Pseudo-Class Selector (`:`)**

   ```css
   a:hover {
     color: pink;
   }
   ```

   _Applies styles when an `<a>` element is hovered over._

7. **Pseudo-Element Selector (`::`)**

   ```css
   p::first-line {
     font-size: 24px;
   }
   ```

   _Styles the first line of all `<p>` elements._

8. **Combinators (Descendant, Child, Adjacent, General Sibling)**
   ```css
   div p {
     color: green;
   }
   ```
   _Selects `<p>` elements inside a `<div>`._

## Conclusion

Understanding the anatomy of a CSS selector is essential for creating structured and effective stylesheets. By mastering different selector types, you can precisely target elements and enhance your web designs efficiently.

For more practice and tutorials, check out [W3 Schools](https://www.w3schools.com/css/default.asp)
