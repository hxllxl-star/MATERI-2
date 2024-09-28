1. Entity
Entity dalam HTML adalah representasi karakter khusus yang tidak bisa ditulis langsung di dalam kode HTML, seperti tanda <, >, &, dan karakter lainnya. Entity ditulis dengan menggunakan format khusus agar browser bisa menampilkan karakter tersebut dengan benar.

Contoh entity yang umum digunakan:
- https://oinam.github.io/entities
- https://html.spec.whatwg.org/multipage/named-characters.html

&lt; : Karakter < (less than)

&gt; : Karakter > (greater than)

&amp; : Karakter & (ampersand)

&quot; : Karakter " (double quote)

&apos; : Karakter ' (single quote)


Kegunaan entity:

Mencegah konflik antara karakter HTML dan teks yang ingin ditampilkan.

Digunakan untuk menampilkan karakter khusus yang tidak ada di keyboard.


Contoh:

<p>Contoh menampilkan tanda lebih kecil: &lt;p&gt;</p>

2. Breakline (<br>)

Breakline atau pemecah baris digunakan untuk memulai baris baru di dalam teks HTML tanpa memulai paragraf baru. Tag ini adalah empty tag, yang berarti tidak memerlukan tag penutup.

Sintaks:

<br>

Kegunaan:

Untuk memecah baris pada tampilan teks di halaman web tanpa menggunakan paragraf baru.


Contoh:

<p>Ini baris pertama.<br>Ini baris kedua setelah breakline.</p>

3. Horizontal Rule (<hr>)

Tag <hr> digunakan untuk menyisipkan garis horizontal yang biasanya digunakan sebagai pemisah antar bagian konten. Seperti <br>, tag ini juga merupakan empty tag.

Sintaks:

<hr>

Kegunaan:

Untuk memberikan pemisah visual antara dua bagian konten.


Contoh:

<p>Paragraf pertama.</p>
<hr>
<p>Paragraf kedua setelah garis horizontal.</p>

Kesimpulan:

Entity digunakan untuk menampilkan karakter khusus dalam HTML.

Breakline (<br>) digunakan untuk membuat baris baru.

Horizontal Rule (<hr>) digunakan untuk membuat garis pemisah.