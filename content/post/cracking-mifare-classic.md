+++
title: "Cracking Mifare Classic"
date: "2022-09-2022"
author: "atr"
+++

## Cracking Mifare Classic 1K

When arriving at university I was given an NFC ID card, complete with a Magstripe as an alternative method of authentication. Using my [Flipper Zero] (https://flipperzero.one/) equipped with a custom firmware that i'm not yet to release, I quickly identified it as a Mifare Classik 1K, a format of NFC card of which I was unfamiliar. After some brief research, [(specifically on Linus Karlsson's blog)] (https://linuskarlsson.se/blog/acr122u-mfcuk-and-mfoc-cracking-mifare-classic-on-arch-linux/) I discovered that the entire cryptographic cipher used on these encrypted NFC cards was reverse engineered by several researchers. Thus, I began the task of using my Flipper (my only NFC interface besides my dated iPhone) to crack my ID card.

> Fusce pharetra suscipit orci nec tempor. Quisque vitae sem sit amet sem mollis consequat. Sed at imperdiet lorem. Vestibulum pharetra faucibus odio, ac feugiat tellus sollicitudin at. Pellentesque varius tristique mi imperdiet dapibus. Duis orci odio, sodales lacinia venenatis sit amet, feugiat et diam.

### Header 3

Nulla libero turpis, lacinia vitae cursus ut, auctor dictum nisl. Fusce varius felis nec sem ullamcorper, at convallis nisi vestibulum. Duis risus odio, porta sit amet placerat mollis, tincidunt non mauris. Suspendisse fringilla, `odio a dignissim pharetra`, est urna sollicitudin urna, eu scelerisque magna ex vitae tellus.

```css
/* PostCSS code */

pre {
  background: #1a1a1d;
  padding: 20px;
  border-radius: 8px;
  font-size: 1rem;
  overflow: auto;

  @media (--phone) {
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  code {
    background: none !important;
    color: #ccc;
    padding: 0;
    font-size: inherit;
  }
}
```

```js
// JS code

const menuTrigger = document.querySelector('.menu-trigger')
const menu = document.querySelector('.menu')
const mobileQuery = getComputedStyle(document.body).getPropertyValue('--phoneWidth')
const isMobile = () => window.matchMedia(mobileQuery).matches
const isMobileMenu = () => {
  menuTrigger.classList.toggle('hidden', !isMobile())
  menu.classList.toggle('hidden', isMobile())
}

isMobileMenu()

menuTrigger.addEventListener('click', () => menu.classList.toggle('hidden'))

window.addEventListener('resize', isMobileMenu)
```

```html
<!-- HTML code -->

<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

#### Header 4

Curabitur scelerisque felis viverra varius scelerisque. Ut enim libero, molestie gravida blandit at, mollis ornare tellus. Cras arcu mi, ultrices vel pulvinar vel, volutpat eu tortor. Nullam nec eros quis massa ultrices iaculis sed in metus. Praesent sollicitudin sem sit amet orci tempor gravida.

- Maecenas elementum vitae nibh vitae porttitor.
- Aenean consequat, risus ut cursus placerat, arcu nulla sodales risus, ut molestie tellus tellus et dui.
- Integer imperdiet turpis vitae lacus imperdiet, ut ornare ligula auctor. Integer in mi eu velit vehicula suscipit eget vulputate nulla.
- Etiam vitae enim quis velit lobortis placerat a ut sem.
  - Curabitur lobortis ante sit amet orci pulvinar, sollicitudin viverra nunc accumsan.
  - Praesent fermentum orci quis leo facilisis posuere.

Aliquam erat volutpat. In hac habitasse platea dictumst. Nunc ut tincidunt mauris. Sed at gravida risus, id semper magna. Nullam vitae enim mattis, sodales neque non, pharetra elit. Cras sit amet sagittis augue, et finibus turpis. Ut tempus tincidunt diam vel pharetra. Nulla porttitor odio sit amet nulla scelerisque, quis aliquam mi imperdiet. Sed tincidunt dui vel tellus vestibulum rhoncus. Donec tempus ultrices velit.
