# 🌟 CSS Revision Notes 🌟

## 🎨 1. Basics of CSS  
**Definition:** CSS (Cascading Style Sheets) is a styling language used to design web pages.

### 📝 Basic Syntax:
```css
selector {
    property: value;
}
```
**Example:**
```css
h1 {
    color: red;
}
```

## 🎨 2. Including CSS  
- ✅ **Inline CSS:** `<h1 style="color: red;">Hello</h1>`  
- ✅ **Internal CSS:**  
  ```html
  <style> h1 { color: red; } </style>
  ```
- ✅ **External CSS:**  
  ```html
  <link rel="stylesheet" href="styles.css">
  ```

## 🌈 3. Colors in CSS  
🎨 **Color Property:** `color: red;`  
🌟 **Background Color:** `background-color: blue;`  
🎨 **Color Systems:**  
```css
color: rgb(255, 0, 0);  
color: #ff0000;
```

## 🔍 4. Selectors  
- ✨ **Universal Selector (`* {}`)**  
- ✨ **Element Selector (`h1 {}`)**  
- ✨ **ID Selector (`#id {}`)**  
- ✨ **Class Selector (`.class {}`)**  

## ✍️ 5. Text Properties  
📌 `text-align: left / right / center;`  
📌 `text-decoration: underline / overline / line-through;`  
📌 `font-weight: normal / bold / 100-900;`  
📌 `font-family: Arial, sans-serif;`  
📌 `text-transform: uppercase / lowercase / capitalize;`  

## 📦 6. Box Model  
```css
height: 50px;  
width: 100px;  
border: 2px solid black;
padding: 10px;  
margin: 20px;
```

## 📌 7. Display & Visibility  
```css
display: inline / block / inline-block / none;
visibility: hidden; /* Hides element but keeps space */
```

## 📍 8. Positioning  
```css
position: static / relative / absolute / fixed / sticky;
z-index: 1;
```

## 🖼️ 9. Backgrounds  
```css
background-image: url("image.jpg");
background-size: cover / contain / auto;
```

## 📐 10. Flexbox  
- **Container Properties:**  
  ```css
  display: flex; 
  justify-content: center;
  ```
- **Item Properties:**  
  ```css
  flex-grow: 1; 
  flex-shrink: 0;
  ```

## 📱 11. Media Queries (Responsive Design)  
```css
@media (max-width: 600px) { 
    div { background-color: red; } 
}
```

## 🔄 12. Transitions & Animations  
```css
transition: all 2s ease-in-out;
@keyframes example { 
    from { opacity: 0; } 
    to { opacity: 1; } 
}
animation: example 2s infinite;
```

🚀 **Happy Coding!** 🎉  
