# Frontend Mentor - Recipe Page Solution

A solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

---

## 📸 Screenshot

![Recipe Page Screenshot](screenshot.png)

---

## 🚀 Live Demo

- [Live Site URL](https://recipe-page-markhording.netlify.app/)
- [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/recipe-page-oijb14e4lr)

---

## 📝 The Challenge

- Build a responsive recipe page from a design.
- Ensure the layout adapts for mobile and desktop.
- Use semantic HTML and accessible markup.

---

## 🛠️ Built With

- Semantic HTML5
- CSS custom properties (variables)
- Flexbox
- Mobile-first workflow
- Vanilla CSS (no frameworks)

---

## 💡 What I Learned

- **Responsive Images:** Used media queries and `object-fit: cover` to make images fill the viewport on mobile.
- **CSS Variables:** Leveraged custom properties for easy color management.
- **Debugging:** Improved skills with browser DevTools for troubleshooting CSS issues.
- **Accessibility:** Focused on semantic tags and alt text for better accessibility.

```css
@media screen and (max-width: 600px) {
  .recipe-image {
    width: 100vw;
    max-width: 100vw;
    height: auto;
    display: block;
    margin: 0;
    border-radius: 0;
    object-fit: cover;
  }
}
```

---

## 🔭 Continued Development

- Explore CSS Grid for more complex layouts.
- Add dark mode support.
- Further improve accessibility and keyboard navigation.

---

## 📚 Useful Resources

- [MDN Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Frontend Mentor Community](https://www.frontendmentor.io/community)

---

## 👤 Author

- Mark Hording
- [Frontend Mentor](https://www.frontendmentor.io/profile/MarkBojeHording)

---

## 🙏 Acknowledgments

Thanks to the Frontend Mentor community for feedback and support!
