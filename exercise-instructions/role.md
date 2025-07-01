
# 📝 Exercise – Role

## 📚 Introduction

Roles provide **semantic meaning** to content, allowing screen readers and other tools to present and support interaction with an object in a way that is consistent with user expectations of that type of object.

---

## 🔧 Usage

ARIA roles can be used to describe elements that don't natively exist in HTML or exist but don't yet have full browser support.

By default, many semantic elements in HTML have a role, for example:

```html
<input type="radio"> <!-- has the "radio" role -->
```

Non-semantic elements in HTML do not have a role;  
`<div>` and `<span>` without added semantics return null. The **role attribute provides semantics** to them.

---

## 📂 Categories of ARIA Roles

- **Document structure roles**: Toolbar, Tooltip, Presentation/None, Feed
- **Widget roles**: Searchbox, Slider, Spinbutton, Switch, Tab, Combobox, Menu
- **Landmark roles**: Banner, Contentinfo, Main, Navigation, Region, Search
- **Live region roles**: Alert, Status, Timer
- **Window roles**: Alertdialog, Dialog

🔗 **Resources:**
- [Mozilla ARIA Roles](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles)
- [WAI ARIA Roles](https://www.w3.org/WAI/ARIA/apg/practices/)

---

## 💻 Exercise

✅ **Task:**  
Identify all interactive elements in your Fiori app and ensure they have an appropriate ARIA role assigned.

✏️ **Example:**  
If you have a custom div acting as a button, assign `role="button"` and ensure it has keyboard interaction and focus styling.

---

✔️ **Validation checklist**

- Does every interactive element have a semantic role?
- Are roles consistent with user expectations?

---
