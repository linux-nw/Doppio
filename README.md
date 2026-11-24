# Doppio

**Status:** ✅ Completed (demo project)

Multi-page coffee website with varieties, recipes, shop info and a simple review system (HTML, CSS, PHP). A concept for learning, not for live use. The company "Doppio GmbH", its contact details and the photos are placeholders.

**Name:** Doppio is Italian for "double", as in a double espresso.

---

## Usage

Serve it on a server with PHP, locally for example with `php -S localhost:8000`, and open it in the browser.

Do not run it on a public server: `save_review.php` writes input to `reviews.json` without a login, without a size limit and without spam protection.

---

## Repo structure

```
index.html, About.html, Shop.html, Contact.html, rezepte.html   pages
stylesheet.css                                                  styling
save_review.php, reviews.json                                   reviews
images/                                                         own or AI-generated images
```

---

## Privacy

No database and no accounts. Reviews are stored unencrypted in `reviews.json` on the server. That is why it should only be used locally.

---

## License

[MIT](LICENSE)
