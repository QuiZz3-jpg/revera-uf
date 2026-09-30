[index.html](https://github.com/user-attachments/files/32868303/index.html)index.html[U[Uploading script.js…]()ploading index.html…]()

style.css [README.md](https://github.com/user-attachments/files/32868329/README.md)
script.js const toggle = document.querySelector('.menu-toggle');
const nav = document.querySelector('.nav');

toggle.addEventListener('click', () => {
  const open = nav.classList.toggle('open');
  toggle.setAttribute('aria-expanded', open);
  toggle.textContent = open ? '×' : '☰';
});

document.querySelectorAll('.nav a').forEach(link => {
  link.addEventListener('click', () => {
    nav.classList.remove('open');
    toggle.setAttribute('aria-expanded', 'false');
    toggle.textContent = '☰';
  });
});
[style.css](https://github.com/user-attachments/files/32868325/style.css)

README.md
# Revèra UF – webbplats

Det här är en helt statisk webbplats och kräver ingen server eller databas.

## Gratis publicering med GitHub Pages

1. Skapa ett gratis konto på GitHub.
2. Skapa ett nytt repository, exempelvis `revera-uf`.
3. Ladda upp `index.html`, `style.css` och `script.js`.
4. Gå till repositoryts **Settings → Pages**.
5. Under "Build and deployment", välj **Deploy from a branch**.
6. Välj `main` och `/ (root)` och spara.
7. Efter en kort stund får ni en gratis adress på GitHub Pages.

## Innan publicering

Ändra gärna:
- Instagram-länken i `index.html`
- E-postadressen i `index.html`
- Produkttexter/bilder när ni har riktiga produkter
- Eventuella färger så att de matchar er slutliga Revèra-logga

Ingen betaltjänst behövs för själva webbplatsen.
