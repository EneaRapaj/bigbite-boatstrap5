README - Big Bite Menu Website
Përshkrimi

Ky projekt është një faqe interneti për një restorant të quajtur Big Bite, e cila paraqet menunë e restorantit me seksione të ndara për Pasta dhe Pizza. Projektet janë ndërtuar duke përdorur HTML, CSS, dhe Bootstrap 5 për të arritur një dizajn të pastër dhe responsiv.

Dy faqet kryesore që përfshihen janë:

1. pasta.html – Menu e pastave.

2. pizza.html – Menu e picave.

Faqet përfshijnë navigacion, seksione menuje, çmime, dhe një footer me imazhe.

Karakteristikat Kryesore
1. Navigacioni

 * Barra navigimi e ndërtuar me Bootstrap 5.

 * Lidhje për Home, About Us, Menu (me dropdown) dhe Contact.

 * Dropdown i menusë ndan artikujt në kategori:

 * Fast Food: Krepa, Sufllaqe, Pizza

 * Restorant: Sallata, Supa, Pasta

2. Seksioni i Pastave (pasta.html)

 * Seksion me titull PASTA.

 * Lista e pastave me:

    * Emrin e produktit

    * Një vijë të pjesshme të stilizuar me CSS dotted line

    * Çmimin për secilën pjatë

* Dizajn fleksibël me flexbox për të rreshtuar elementet (emër dhe çmim) në një rresht.

3. Seksioni i Picave (pizza.html)

  * Seksion me titull MENU PICA.

  * Lista e picave me:

      * Emrin e produktit

      * Përbërësit e picës

      * Çmimin

* Dizajn fleksibël me flexbox dhe klasat .rregullimi, .rregullimin1, .rregullimin2, etj.,
  për të rregulluar pozicionin e çmimeve dhe përbërësve.

* Përdorim i ngjyrave për të theksuar titujt dhe përbërësit: text-warning për tituj dhe përbërës, text-white për titullin kryesor.

4. Footer

  * I përfshirë në të dyja faqet.

  * Shfaq një imazh të footer-it (img/Capture77.jpg) që përfaqëson brandin.

Teknologjitë e Përdorura

   * HTML5 – Strukturë bazë e faqeve.

   * CSS – Stilet e personalizuara për menunë dhe pozicionimin e elementeve.

   * Bootstrap 5 – Për dizajn responsiv dhe navigacion.

Strukturimi i Kodit

* Header: Navbar me dropdown menu.

     * Seksioni Kryesor:

      * .container për mbajtjen e menusë.

      * .flex-container për rreshtimin horizontal të emrit të produktit dhe çmimit.

      * .menu, .menu-title, .menu-dottet, .cmim-menu për stilizim të detajuar.

    * Footer: Imazh i footer-it.

   * Scripts: Përfshirja e Bootstrap.bundle.min.js për funksionalitetin e navbar dhe dropdown.

Si të përdoret

  1. Klono ose shkarko projektin.

  2. Sigurohu që folderi img përmban të gjitha imazhet:

    * bblogo.png

    * Capture77.jpg

 3. Hap pasta.html ose pizza.html në shfletuesin tuaj për të parë menunë.

Sugjerime për Përmirësim

    * Shtimi i një database për menunë për të bërë faqen dinamike.

    * Përdorimi i JavaScript për filtrimin e menusë sipas kategorive.

    * Përmirësimi i dizajnit për pajisje mobile duke përdorur media queries.
