---

theme: black
highlightTheme: css/vs2015.css

margin: 0.1

width: 960

height: 640



bg: '#000'

progress: true

center: true
---
<grid align="center" drop="center" drag="70 35" style="background-color:#1c1c1c; border-radius:64px;">
# Hogyan teszteljünk?  <!-- element  style="font-size:2.4em"-->


### <i class="far fa-flag fa-lg"></i> Capture The Flag versenyek 

</grid>

<grid drag="100 10" drop="0 75" align="center"  >

<a href="https://ersok.hu"><i class="fas fa-home fa-1x" alt="`fas:Home`" /></a> Érsok Máté <!-- .element style="color:#505050;" -->

<span style="font-size:0.9em; color:#505050; padding:0px; margin:0px; text-align:center!important;">Magyar Tudomány Ünnepe </br>2022.11.17.</span>

</grid>

<grid drag="20 10"drop="bottomright"  align="bottomright">

<img src="https://nik.uni-obuda.hu/wp-content/uploads/2020/09/cropped-nik_inv_edited.png" height="40"/>

</grid>

---

<!-- slide template="[[slide-template]]" -->

# AGENDA


<grid drag="55 15" drop="40 10" bg="#5B799E" align="center" pad="0 15px" style="border-radius:24px" justify-content="center">
## Tesztelési lehetőségek <!-- element style="font-size:2em" -->
</grid>

<grid drag="35 15" drop="40 30" bg="#AE6225" align="center" pad="0 15px" style="border-radius:24px">
## CTF verseny <!-- element style="font-size:2em" -->
</grid>

<grid drag="55 15" drop="40 50" bg="#802534" align="center" pad="0 15px" style="border-radius:24px">
## Megoldanó problémák <!-- element style="font-size:2em" -->
</grid>

<grid drag="35 15" drop="40 70" bg="#538071" align="center" pad="0 15px" style="border-radius:24px">
## Lehetőségek <!-- element style="font-size:2em" -->
</grid>


---



<!-- slide template="[[slide-template]]"-->
# Security eszköz tesztelése/értékelése

- Saját támadási módszerek  
- Meglévő automata eszközök
- Internetet fürkésző botok
- Felbérelhetünk hivatásos hackereket

---
<!-- slide template="[[slide-template]]" bg="#000"-->

# Vállalati biztonsági eszköz értékelése

1. Követelmények összegyűjtése
2. Tesztelési keretek meghatározása
	- Cél rendszerek
	- Figyelő rendszer meghatározása
	- Sérülékeny alkalmazás
	- Támadó eszköz 
3. Támadási  terv
   - Felderítés
   - Támadási kísérletek
   - Jogosultság szerzés
4. Eredmények pontozása


---

# Akkor készen is vagyunk? <!-- element style="font-size:2.8em" -->

<grid drag="20 10"drop="bottomright"  align="bottomright">

<img src="https://nik.uni-obuda.hu/wp-content/uploads/2020/09/cropped-nik_inv_edited.png" height="40"/>

</grid>
---
<!-- slide template="[[slide-template]]" -->

# Problémák
- Egy támadó **nincs korlátozva**
- Kicsi adatkészlet, kicsi szórással
- Új sérülékenységek



<grid drag="80 100" drop="35 -10" style="text-align:center">
<div style="width:550px; height:650px; overflow:hidden">
     <img src="/PREZI/assets/adnan-khan-VS2C5_GI_MM-unsplash.jpg"> <!--.element style="overflow:hidden;object-fit: cover;width: 550px;height: 650px;" -->
</div>
</grid>

---
<!-- slide template="[[slide-template]]" -->
<grid drag="40 20" drop="topleft">
# Capture the Flag!
</grid>


<grid drop="left">
> CTF competitions: what are they? Capture-the-Flag events are **computer security competitions**. Participants compete in security-themed challenges for the purpose of obtaining the highest score. Competitors are expected to “capture flags” to increase their score, hence the name of the event.
</grid>

<grid drop="50 30" align="topleft"   >

### Előnyök

- Gyakorlási lehetőség
- Valósabb környezet
	- Résztevők számára
	- Elemzők számára
	- Nagyobb terhelés
- Sokkal nagyobb és színesebb adathalmaz
- Különböző védelmi eszközök összehasonlítása
</grid>


---
<grid drag="48 10" drop="topleft" >
# Általános CTF architektúra
</grid>

<grid drag="80 100" drop="10 0" >
<img src="/PREZI/assets/CTF_archi.svg" style="max-width:80%;" > <!-- .element align="stretch" -->
</grid>

<grid drag="20 10" drop="bottomright"  align="bottomright">

<img src="https://nik.uni-obuda.hu/wp-content/uploads/2020/09/cropped-nik_inv_edited.png" height="40"/>

</grid>

---
<!-- slide template="[[slide-template]]" -->

# CTF verseny eseményei

![[/PREZI/assets/ctf-event.png]]


---
<!-- slide template="[[slide-template]]" -->

# Általunk használt 
# megoldások

- ctftime.org
- CTFd
- Docker
- OpenVPN
  
  
<grid drag="60 80" drop="40 5" bg="#BDC8D2" style="border-radius:64px">
![[/PREZI/assets/honeysystem_ctf.drawio.png]]
Az általunk használt infrastruktúra
</grid>

---
<!-- slide template="[[slide-template]]" -->

# Általunk használt 
# megoldások

- ctftime.org
- CTFd
- Docker
- ansible
- Terraform
- OpenVPN
  
  
<grid drag="60 80" drop="40 5">
![[/PREZI/assets/arch.drawio(1).svg]]
Az általunk használt infrastruktúra
</grid>

---
<!-- slide template="[[slide-template]]" -->
# Megoldandó problémák
- Webes felület (tovább) fejlesztése
- Automatizált build folyamat
- Új népszerű sérülékenységek gyűjtése
	- **Attack Graph** alkamazása
- Jelenlegi infrastruktúra optimalizálása

<grid drag="55 50" drop="46 30">
![[/PREZI/assets/score-board.png]] <!-- element style="border-radius:24px" -->
*CTFd* eredményjelző felülete
</grid>



---
<!-- slide template="[[slide-template]]" -->
# Megoldandó problémák
- Webes felület (tovább) fejlesztése
- Automatizált build folyamat
- Új népszerű sérülékenységek gyűjtése
	- **Attack Graph** alkamazása
- Jelenlegi infrastruktúra optimalizálása

<grid drag="50 40" drop="50 30">
![[/PREZI/assets/CICDBlog.webp]]
*Continuous integration, continuous delivery*
</grid>

---
<!-- slide template="[[slide-template]]" -->
# Megoldandó problémák
- Webes felület (tovább) fejlesztése
- Automatizált build folyamat
- Új népszerű sérülékenységek gyűjtése
	- **Attack Graph** alkalmazása
- Jelenlegi infrastruktúra optimalizálása

<grid drag="50 80" drop="50 5" >
![[/PREZI/assets/Screenshot 2022-11-17 at 12.27.18.png ]] <!-- element style="border-radius:24px" -->
*National Vulnerability Database* adatai
</grid>

---
<!-- slide template="[[slide-template]]" -->
# Lehetőségek <!-- element style="font-size:2.8em" -->
---
<!-- slide template="[[slide-template]]" -->
# Kutatás & Fejlesztés

- CTF kihívások fejlesztése
- Dinamikus kihívások
- Optimalizálás - CI/CD
- Webfejlesztés - a versenyhez kapcsolódó platform
- Speciális területek kihívásai
	- 5G
	- IoT
	- OT
	- ...
---
<grid drag="30 10" drop="topleft" >
# A csapat tagjai
</grid>

<grid drag="25 40" drop="0 10" style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/bbanna.jpg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 150px;height: 150px;" -->
</div>
Bánáti Anna
</grid>

</div>
<grid drag="25 40" drop="25 10" style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/erdodi.png"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 150px;height: 150px;" -->
</div>
Erdődi László
</grid>

<grid drag="25 40" drop="50 10" style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/BaloghAdam.jpg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 150px;height: 150px;" -->
</div>
Balogh Ádám
</grid>

<grid drag="25 40" drop="75 10" style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/_MG_2683.png"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 150px;height: 150px;" -->
</div>
Érsok Máté
</grid>


<!-- adséflkasjdélf -->
<grid drag="14 28" drop="85 55"  style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/assets/HL.jpeg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 100px;height: 100px;" -->
</div>
Hegedűs Dániel
</grid>

<grid drag="14 28" drop="1 55" style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/assets/kakonyibalint.jpeg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 100px;height: 100px;" -->
</div>
Kákonyi Bálint
</grid>

<grid drag="14 28" drop="15 55"  style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/assets/SzaboMarton.jpeg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 100px;height: 100px;" -->
</div>
Szabó Márton
</grid>

<grid drag="14 28" drop="29 55"  style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/assets/nd.jpeg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 100px;height: 100px;" -->
</div>
Németh Donát
</grid>
<grid drag="14 28" drop="43 55"  style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/assets/hg.jpeg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 100px;height: 100px;" -->
</div>
Havassy Gergely
</grid>
<grid drag="14 28" drop="57 55" style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/assets/UP.jpeg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 100px;height: 100px;" -->
</div>
Urbanics &nbsp Pál
</grid>
<grid drag="14 28" drop="71 55"  style="text-align:center">
<div style="width:180px; height:180px; overflow:hidden">
     <img src="/PREZI/assets/SK.jpeg"> <!--.element style="border-radius: 100%;overflow:hidden;object-fit: cover;width: 100px;height: 100px;" -->
</div>
Somogyi Kristián
</grid>


<grid drag="20 10"drop="bottomright"  align="bottomright">

<img src="https://nik.uni-obuda.hu/wp-content/uploads/2020/09/cropped-nik_inv_edited.png" height="40"/>

</grid>

---
<grid drag="48 10" drop="topleft" >
# Versenyek
</grid>




<grid drag="60 60" drop="0 0" style="font-size:26px; text-align:left">
> [!info]
> A **HCSC 2022** infrastruktúráját és CTF kihívásait csapatunk  készítette és terveik szerint ez az elkövetkező években is így lesz.
</grid>

<grid drag="60 60" drop="30 35" style="font-size:32px; text-align:left">
> [!Warning]
> 2022.11.25-én kezdődik a kari CTF versenyünk, melyre várunk minden érdeklődőt! 
</grid>



<grid drag="20 10"drop="bottomright"  align="bottomright">

<img src="https://nik.uni-obuda.hu/wp-content/uploads/2020/09/cropped-nik_inv_edited.png" height="40"/>

</grid>
---


<!-- slide template="[[slide-template]]" -->

# Kérdés?

Photo by [Vimal S](https://unsplash.com/@vimal_saran?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/t/3d-renders?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

Photo by <a href="https://unsplash.com/@adnan10?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Adnan Khan</a> on <a href="https://unsplash.com/s/photos/mask?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Photo by <a href="https://unsplash.com/@tar1k?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tarik Haiga</a> on <a href="https://unsplash.com/s/photos/mask?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  


<a href="https://www.freepik.com/free-psd/waving-flag-mockup_19564707.htm#page=2&query=flag&position=10&from_view=search&track=sph">Flag mockup by user6702303</a> on Freepik

<grid drag="55 50" drop="46 20">
 <i class="far fa-flag fa-7x"></i><!-- element style="font-size:20em; color:#802534" -->
</grid>


<style>

:root {

--callout-radius:5px;

--r-math-color:#FAFAFA;

--cm-inline-background: #242424;

--cm-inline-foreground: #802534;

--r-heading-text-transform: none;

--primaryBorderColor: #666666;

--r-heading-font: 'Inter', 'Arial', "OpenSans-Bold", "Open Sans", Helvetica, Impact, sans-serif;

--r-main-background-color: #000!important;

--r-main-font: 'Inter', "Arial", "Open Sans", "Coming Soon", "SourceSansPro", Helvetica Neue, sans-serif;

--r-heading-letter-spacing: -0.45px;

--r-heading-word-spacing: 0.5px;

--r-heading-text-transform: none;

--r-heading-text-shadow: none;

--r-heading-font-weight: 700;

--r-heading1-text-shadow: none;

--r-main-font-size: 22px;

--r-main-line-height: 1.5em;

--r-monospace-font-size: 18px;

--r-heading1-size: 1.6em;

--r-heading2-size: 1.25em;

--r-heading3-size: 1.2em;

--r-heading4-size: 1.15em;

--r-heading5-size: 1.05em;

--r-heading6-size: 1.025em;

--r-heading-line-height:1.5em;

--r-main-font-family: 'Inter';

--r-code-font: "JuliaMono", "agave Nerd Font", "Hack", "VictorMono", monospace;

--r-link-color: #802534;

--r-link-color-dark: #f92672;

--r-link-color-hover: #63ff51;

--r-accent-color: #77CA29;

--r-controls-color: #802534;

--r-progress-color: #802534;

--r-header-accent: #D5325D;

--r-selection-background-color: RGBA(255, 255, 0, 0.15);

--r-selection-color: RGB(255, 255, 0);

--r-main-color: #fff;

--text-muted: #fff;

--text-faint: #404040;

--r-heading-color: #FFF;

--r-background-color: #1c1c1c;

--cm-keyword: #c792ea;

--cm-atom: #f78c6c;

--cm-number: #ff5370;

--cm-type: #decb6b;

--cm-def: #82aaff;

--cm-property: #c792ea;

--cm-variable: #f07178;

--cm-variable-2: #EEFFFF;

--cm-variable-3: #f07178;

--cm-definition: #82aaff;

--cm-callee: #89ddff;

--cm-qualifier: #decb6b;

--cm-operator: #89ddff;

--cm-hr: #98e342;

--cm-link: #696d70;

--cm-header: #da7dae;

--cm-builtin: #ffcb6b;

--cm-meta: #ffcb6b;

--cm-matching-bracket: #FFFFFF;

--cm-tag: #ff5370;

--cm-tag-in-comment: #ff5370;

--cm-string-2: #f07178;

--cm-bracket: #ff5370;

--cm-comment: #676e95;

--cm-string: #c3e88d;

--cm-attribute: #c792ea;

--cm-attribute-in-comment: #c792ea;

--cm-background-color: #1c1c1c;

--cm-active-line-background-color: #353a50;

--cm-foreground-color: #AE81FF;

--code-normal: #AE81FF;

-webkit-font-smoothing:subpixel-antialiased;

--font-smoothing:subpixel-antialiased;

--chart-color-1: #ff00ff;

--chart-color-x: RGB(255.0,255.0,255.0);

}

.standout{

background: var(--cm-background-color);

padding:5px;

font-weight:700;

border-radius:6px;

}

.reveal pre {

display:block;

margin:auto;

width:auto;

font-family: var(--r-code-font);

font-size: var(--r-monospace-font-size);

padding: auto;

white-space: pre-wrap;

}

.reveal p {

margin:auto!important;

padding:auto!important;

}

.reveal pre code {

display: inline-block;

top: 2px;

white-space: pre;

bottom: 2px;

margin:auto;

padding:auto;

font-size: 0.8em;

background:var(--cm-background-color);

color: var(--cm-foreground-color)!important;

text-align: justify;

letter-spacing: -0.45px!important;

word-spacing: -0.5px!important;

}

.reveal {

font-family: var(--r-main-font), sans-serif;

font-size: var(--r-main-font-size);

font-weight: normal;

color: var(--r-main-color);

background-color: var(--r-main-background-color);

}

.reveal blockquote p {

color: var(--text-muted);

font-style: normal !important;

font-align: left;

display: inline;

text-align: left;

}

.reveal blockquote em{

color: var(--text-muted);

text-align: left;

}

.reveal blockquote {

border-radius: 8px !important;

margin: 0.5rem 0rem 0.5rem 0rem;

text-align: left;

padding-top: 1rem;

padding-left: 2rem;

padding-bottom: 1rem;

padding-right: 2rem;

width: auto;

font-style: normal !important;

}

.reveal blockquote {

font-size: unset;

margin: auto;

padding:auto;

}

.reveal ul, ol {

text-align:left;

}

.reveal ul ul,

.reveal ul ol,

.reveal ol ol,

.reveal ol ul {

text-align:left;

}

.reveal ul ul {

list-style: circle;

}

.container {

position: relative;

}

.make-it-pop {

filter: drop-shadow(0 0 10px purple);

}

@media (max-width: 95%) {

section {

-webkit-flex-direction: column;

flex-direction: column;

}

}

.footer {

font-size: 60%;

vertical-align:bottom;

color:#bdbdbd;

font-weight:400;

margin-left:-5px;

}

.note {

color:#f8f8f8;

border-radius:8px;

background-color:#35353540;

width: max-content;

border-color:#66666640;

padding: auto;

margin:auto;

}

#blue {

color: #00CCFF;

}

#red {

color: #FF5252;

}

.callout {

overflow: hidden;

border-style: none;

border-color: RGBA(var(--callout-color), var(--callout-border-opacity));

border-width: var(--callout-border-width);

border-radius: var(--callout-radius);

margin: 1em 0;

mix-blend-mode: var(--callout-blend-mode);

background-color: rgba(var(--callout-color), 0.1);

padding: var(--callout-padding);

}

.callout-title {

font-size: var(--callout-title-size);

color: RGB(var(--callout-color));

background-color: RGB(var(--callout-color), 0.0);

line-height: var(--line-height-tight);

font-weight: 700;

}

.callout-content {

overflow-x: auto;

padding: auto;

background-color: var(--callout-content-background);

}

.callout-icon {

flex: 0 0 auto;

padding: auto;

display: flex;

align-self: center;

}

.callout-icon .svg-icon {

color: RGB(var(--callout-color));

}

.callout-title-inner {

font-weight: var(--bold-weight);

color: var(--callout-title-color);

}

.callout-fold {

display: flex;

align-items: center;

padding-right: var(--size-4-2);

}

.reveal .code-wrapper code {

width: 98%;

}
.reveal .progress {
  color: var(--r-controls-color);
}

.reveal code {

font-family: var(--r-code-font);

text-transform: none;

tab-size: 4;

background-color:var(--cm-background-color);

color: var(--cm-foreground-color);

border-radius:2px;

letter-spacing: -0.45px!important;

word-spacing: -0.5px!important;

}

.reveal pre code {

padding: auto;

border:none;

border-radius:2px;

font-size:0.9em;

margin:auto;

background: var(--cm-background-color);

}

.reveal p code {

font-family: var(--r-code-font);

text-transform: none;

tab-size: 4;

padding:auto;

font-size:0.9em!important;

line-height:inherit;

background:var(--cm-inline-background);

color: var(--cm-inline-foreground);

border-radius:3px;

letter-spacing: -0.45px!important;

word-spacing: -0.5px!important;

}

mjx-container[jax="CHTML"][display="true"] mjx-math {

color: var(--r-math-color);

}

mjx-math {

color: var(--r-math-color);

background: none!important;

padding:unset;

vertical-align:inherit;

}

#customcontrols > ul {

display: none!important;

}

#customcontrols button {

display: none!important;

}

.reveal .slides > section.present, .reveal .slides > section > section.present {

min-height: 100% !important;

display: flex !important;

flex-direction: column !important;

justify-content: center !important;

position: absolute !important;

top: 0 !important;

}

section > h1 {

position: absolute !important;

top: 0 !important;

margin-left: auto !important;

margin-right: auto !important;

left: 0 !important;

right: 0 !important;

}

h1 {

border-bottom: 3px solid var(--r-header-accent);

text-align: left!important;

min-width: max-content;

max-width: min-content;

}

.print-pdf .reveal .slides > section.present, .print-pdf .reveal .slides > section > section.present {

min-height: 770px !important;

position: relative !important;

}

.hljs {

background: var(--cm-background-color) !important;

font-size:inherit;

}

.hljs-main {

color: #ff5252

}

.hljs-built_in {

color: #63ff5b;

}

.hljs-comment, .hljs-quote, .hljs-deletion {

color: #454545;

}

.hljs-params{

color: #03A9F4;

}

.hljs-meta {

color: #AE81FF;

}

.hljs-string {

color: #FFFF00;

}

strong {

color: #C4415F!important;

font-weight: 700;

}

ul {

margin-left: 0;

padding-left:1em;

}

ol {

margin-left: 0;

padding-left:1em;

}

.reveal .code-wrapper code {

st white-space: unset;

}

.reveal pre {

white-space: pre-wrap;

}

.reveal sup {

font-size:0.6em;

}

.markdown-rendered code {

color: var(--code-normal)!important;

font-family: var(--font-monospace);

}

body.fallback-highlighting[class*="theme-"] .markdown-preview-view pre.cm-s-obsidian[class*="language-"], body.fallback-highlighting[class*="theme-"] .markdown-preview-view code[class*="language-"], body.fallback-highlighting[class*="theme-"] .markdown-preview-view .HyperMD-codeblock, body.fallback-highlighting[class*="theme-"] .markdown-preview-view .cm-hmd-codeblock {

--font-monospace: var(--cm-font-monospace);

color: var(--cm-foreground-color);

font-family: var(--cm-font-monospace);

font-weight: var(--cm-font-weight);

line-height: var(--cm-line-height);

font-size: var(--cm-font-size);

white-space: var(--cm-wrap-lines);

}

.reveal .code-wrapper code {

color: #B0BEC5;

font-family: var(--r-code-font);

font-size: 18px;

line-height:1.1em;

}

</style>

<script> var config = { theme: 'default', logLevel: 'fatal', securityLevel: 'strict', startOnLoad: true, arrowMarkerAbsolute: false, er: { diagramPadding: 20, layoutDirection: 'TB', minEntityWidth: 100, minEntityHeight: 75, entityPadding: 15, stroke: 'gray', fill: 'honeydew', fontSize: 12, useMaxWidth: true, }, flowchart: { diagramPadding: 8, htmlLabels: true, curve: 'basis', }, sequence: { diagramMarginX: 50, diagramMarginY: 10, actorMargin: 50, width: 150, height: 65, boxMargin: 10, boxTextMargin: 5, noteMargin: 10, messageMargin: 35, messageAlign: 'center', mirrorActors: true, bottomMarginAdj: 1, useMaxWidth: true, rightAngles: false, showSequenceNumbers: false, }, gantt: { titleTopMargin: 25, barHeight: 20, barGap: 4, topPadding: 50, leftPadding: 75, gridLineStartPadding: 35, fontSize: 11, fontFamily: '"Open Sans", sans-serif', numberSectionStyles: 4, axisFormat: '%Y-%m-%d', topAxis: false, }, }; mermaid.initialize(config); </script>