# Tipe-1

```html
<div class="input-container">
    <span class="input-logo" >@</span>
    <input type="text" class="input" placeholder="Username" >
</div>
```

```css
.input-container {
    position: relative;
    display: flex;
    align-items: stretch;
    width: 100%;
}

.input-logo {
    display: flex;
    align-items: center;
    padding: 0.375rem 0.75rem;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    text-align: center;
    white-space: nowrap;
    background-color: #e8e9eb;
    border: 1px solid #ced4da;
    border-radius:  0.375rem 0rem 0rem 0.375rem;
  }

.input {
  display: inline;
  width: 100%;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ced4da;
  border-left: none;
  appearance: none;
  border-radius: 0rem 0.375rem 0.375rem 0rem;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}
```

