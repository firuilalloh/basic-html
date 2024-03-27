## Basic HTML
>[!NOTE]
>For beginer

### Apa itu HTML
HTML ( Hypertext Markup Language ) adalah sebuah markup language yg menunjukkan bagaimana structur web yg kalian kunjungi.

### HTML Anatomy
![html-anatomy](/image//grumpy-cat-small.png)

The opening tag : Ini terdiri dari nama elemen e.g tag h1, h2, h3, span, dll. (dalam contoh ini, p untuk paragraf), dibungkus dalam kurung siku pembuka dan penutup. Tag pembuka ini menandai di mana elemen dimulai atau mulai berlaku.

The content : ini adalah elemnt content. di dalam contoh ini, ini adalah text paragraf

The closing tag : ini sebenernya sama dengan openign tag. cuman di bagian closing tag ini kalian tambahin / sebelum nama element

### Nesting Element
Element bisa di taruh dengan element yg lain, ini di sebut dengan nesting. e.g.
```html
<p>this cat is <strong>very</strong> grumpy</p>
```

![nesting-element](/image/Screenshot%20from%202024-03-27%2009-11-37.png)

### Void Element
ngga semua element harus mengukuti pola opening tag, content dan closing tag. ada beberapa elemnt yg berdiri dengan single tag. yang biasanya digunakan untuk menyisipkan/menyematkan sesuatu ke dalam dokumen. Elemen seperti ini disebut elemen kosong. Misalnya, elemen img menyematkan file gambar ke halaman:

```html
<img
  src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png"
  alt="Firefox icon" />
```
![single-tag](/image/Screenshot%20from%202024-03-27%2009-18-12.png)

### Attributes
Semua element bisa memiliki attribute. contoh attribute seperti ini:

![atributes](/image/grumpy-cat-attribute-small.png)

Atribut berisi informasi tambahan tentang elemen yang tidak akan muncul di konten. Dalam contoh ini, atribut class adalah nama pengenal yang digunakan untuk menargetkan elemen pada informasi style.

dan attribute sebaiknya mempunyai:
- jarak antara nama attribute dengan element 
- kemudian attribute name, yg di ikuti dengan tanda sama dengan
- attribute value yg di bungkus dengan pembuka dan penutup tanda quote

Elemen img dapat mengambil sejumlah atribut, termasuk:

- `src`

&nbsp; sebuah attribut `src` ini di perlukan untuk menentukan lokasi image kalian, contoh:
`src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png"`

- `alt` 

attribut `alt` menentukan deskripsi text pada gambar yg tidak tampil, contoh : `alt="The Firefox icon"`

- `width`

atribut `width` menentukan lebar dari gambar.

- `height`

atribut `height` menentukan panjang dari gambar.

