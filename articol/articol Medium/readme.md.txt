Răspunsul tău:
http://output.jsbin.com/jobeweh/


Ai învățat următoarele lucruri noi în acest proiect:

HTML
<title>Titlul paginii</title>

<h1>Cea mai importantă rubrică</h1>
<h6>Cea mai puțin importantă rubrică</h6>

<figure>
  <img src="http://nume-imagine.jpg" alt="text alternativ">
  <figcaption>Legendă pentru imagine</figcaption>
</figure>

<article>
  <p>Paragraf <a href="http://link-către-ceva.com" title="Titlul paginii din link">cu link pe care se poate da clic</a></p>
  <p>Alt paragraf <strong>cu conținut important</strong>.</p>
</article>


CSS
h1 {
  color:          rgba(0,0,0,.8);     // culoare, (red, green, blue, opacity (alpha))
  font-family:    serif;              // tip font
  font-size:      36px;               // mărime font
  line-height:    1.58;               // înălțime linie
  letter-spacing: -.003em;            // spațiu între litere
  text-align:     center;             // aliniere text
}

img {
  height:         auto;               // înălțime imagine
  width:          100%;               // lățime imagine
}

figure {
  margin:         0;                  // margine
}

article {
  margin:         0 auto;             // centrat
}

a:hover {
                                      // starea când se trece cu mouse-ul
}