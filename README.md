# Nova-ia-
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#050816">
<title>NOVA AI — Your digital world, powered by AI</title>
<style>
:root{--bg:#050816;--panel:#0d1227;--panel2:#111936;--line:#242b55;--white:#f7f8ff;--muted:#b9c1dc;--purple:#8b3dff;--blue:#287bff;--cyan:#23c8ff}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:radial-gradient(ellipse at 80% 10%,#151044 0,transparent 32%),var(--bg);color:var(--white);font-family:Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;line-height:1.55}
a{color:inherit;text-decoration:none}.wrap{width:min(1160px,92%);margin:auto}
header{position:sticky;top:0;z-index:10;background:rgba(5,8,22,.88);backdrop-filter:blur(16px);border-bottom:1px solid rgba(115,105,220,.18)}
.nav{height:76px;display:flex;align-items:center;justify-content:space-between;gap:18px}.brand{display:flex;align-items:center;gap:10px;font-weight:850;font-size:25px;letter-spacing:-1px}.mark{width:38px;height:38px;border-radius:12px;background:linear-gradient(135deg,var(--purple),var(--blue));display:grid;place-items:center;font-weight:900;font-size:23px;box-shadow:0 0 25px #693bff55}.brand span:last-child{color:#a87bff}
nav{display:flex;gap:28px;color:#e2e5f5;font-size:14px}nav a:hover,.textlink:hover{color:#b99aff}
.btn{border:0;border-radius:999px;padding:13px 21px;background:linear-gradient(110deg,var(--purple),var(--blue));color:white;font-weight:750;cursor:pointer;box-shadow:0 8px 28px #6338ff38;display:inline-flex;align-items:center;justify-content:center;gap:8px}.btn.secondary{background:#111936;border:1px solid #343b70;box-shadow:none}.btn.small{padding:10px 15px;font-size:13px}
.menu{display:none;background:transparent;color:white;border:1px solid var(--line);border-radius:10px;padding:8px 11px;font-size:20px}
.hero{padding:78px 0 48px;display:grid;grid-template-columns:1.08fr .92fr;align-items:center;gap:30px;min-height:550px}
.eyebrow{display:inline-flex;align-items:center;gap:8px;padding:7px 13px;border:1px solid #4930a1;background:#151033;border-radius:999px;color:#d5c7ff;font-size:13px}
h1{font-size:clamp(42px,6vw,70px);line-height:1.03;letter-spacing:-3px;margin:22px 0 18px;max-width:700px}h1 .gradient,.grad{background:linear-gradient(100deg,#a24bff,#3d9cff);-webkit-background-clip:text;background-clip:text;color:transparent}
.lead{font-size:17px;color:var(--muted);max-width:620px}.actions{display:flex;gap:13px;flex-wrap:wrap;margin-top:27px}
.visual{height:400px;position:relative;display:grid;place-items:center;overflow:hidden}.orb{position:absolute;width:310px;height:310px;border-radius:50%;background:radial-gradient(circle at 35% 30%,#6e42ff,#1d2b89 40%,#090d25 72%);filter:drop-shadow(0 0 65px #653dff77);opacity:.8}.ring{position:absolute;width:420px;height:130px;border:3px solid #573bff;border-radius:50%;transform:rotate(-18deg);box-shadow:0 0 24px #4c6bff}.ring.two{width:360px;height:110px;transform:rotate(28deg);border-color:#16bfff;opacity:.7}
.ai-core{position:relative;width:205px;height:245px;border-radius:48% 48% 42% 42%;background:linear-gradient(145deg,#d7dcff,#626fbd 30%,#151c48 70%);box-shadow:inset -18px -15px 35px #080d2d, inset 12px 10px 22px #fff8,0 0 45px #6d57ff66;clip-path:polygon(18% 0,82% 0,100% 25%,91% 78%,70% 100%,30% 100%,9% 78%,0 25%)}
.ai-core:before{content:"";position:absolute;left:18%;right:18%;top:33%;height:35px;border-radius:50px;background:linear-gradient(90deg,#1b2365,#05091b);box-shadow:0 0 18px #8a58ff}.ai-core:after{content:"";position:absolute;left:32%;right:32%;top:45%;height:5px;border-radius:9px;background:#a98cff;box-shadow:0 0 18px #9a63ff}
.visual-label{position:absolute;bottom:20px;right:4%;color:#c7c9ff;font-size:12px;letter-spacing:2px}
.section{padding:55px 0}.section-head{display:flex;align-items:end;justify-content:space-between;gap:20px;margin-bottom:24px}.section h2{font-size:clamp(28px,4vw,39px);letter-spacing:-1.4px;margin:0}.sub{color:var(--muted);margin:8px 0 0}
.cards{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}.card{background:linear-gradient(150deg,#111832,#090e20);border:1px solid var(--line);border-radius:20px;padding:22px;min-height:170px;transition:.2s}.card:hover{transform:translateY(-4px);border-color:#6950d7;box-shadow:0 15px 35px #0005}.ico{width:43px;height:43px;border-radius:13px;background:#25164a;color:#ad7aff;display:grid;place-items:center;font-size:22px;margin-bottom:14px}.card h3{margin:0 0 5px;font-size:18px}.card p{margin:0;color:var(--muted);font-size:14px}
.tool-layout{display:grid;grid-template-columns:1fr 1fr;gap:18px}.toolbox{background:linear-gradient(145deg,#101832,#090e20);border:1px solid var(--line);border-radius:20px;padding:24px}.toolbox label{display:block;font-size:13px;color:#d6d9ed;margin:14px 0 7px}.field,textarea,select{width:100%;background:#070c1d;border:1px solid #30385f;border-radius:12px;padding:12px 13px;color:white;font:inherit;outline:none}.field:focus,textarea:focus{border-color:#9364ff}textarea{min-height:100px;resize:vertical}.output{background:#080d20;border:1px dashed #454b7d;border-radius:12px;padding:14px;color:#dbe0ff;min-height:90px;margin-top:13px;white-space:pre-wrap}
.products{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}.product{background:linear-gradient(145deg,#111832,#090e20);border:1px solid var(--line);border-radius:18px;padding:20px}.product .cover{height:115px;border-radius:13px;background:radial-gradient(circle at 70% 20%,#4f3ac1,#17133c 45%,#080d20);display:grid;place-items:center;font-size:37px;margin-bottom:16px}.price{font-weight:800;font-size:22px;margin:12px 0}.tag{display:inline-block;color:#cbb4ff;background:#241743;padding:4px 9px;border-radius:99px;font-size:11px}
.notice{border:1px solid #51438b;background:#151033;color:#d9d1ff;border-radius:14px;padding:14px 16px;font-size:13px;margin-top:18px}
footer{border-top:1px solid var(--line);padding:28px 0;color:#aeb6d4;font-size:13px;margin-top:35px}.foot{display:flex;justify-content:space-between;gap:15px;flex-wrap:wrap}
.mobile-only{display:none}
@media(max-width:850px){nav{gap:14px}.hero{grid-template-columns:1fr;padding-top:55px}.visual{height:300px;grid-row:1}.cards{grid-template-columns:repeat(2,1fr)}}
@media(max-width:600px){.nav{height:66px}.brand{font-size:21px}.nav>.btn{display:none}.menu{display:block}nav{display:none;position:absolute;top:66px;left:0;right:0;background:#080d20;padding:18px 5%;border-bottom:1px solid var(--line);flex-direction:column}nav.open{display:flex}.hero{padding-top:32px;gap:8px;min-height:auto}.visual{height:245px}.orb{width:205px;height:205px}.ring{width:290px;height:90px}.ring.two{width:250px;height:75px}.ai-core{width:145px;height:180px}h1{font-size:43px;letter-spacing:-2px}.lead{font-size:15px}.section{padding:38px 0}.cards{gap:10px}.card{padding:16px;min-height:155px}.card h3{font-size:16px}.card p{font-size:12px}.tool-layout,.products{grid-template-columns:1fr}.section-head{display:block}.section-head .btn{margin-top:14px}.foot{display:block}.foot div+div{margin-top:8px}}
</style>
</head>
<body>
<header>
 <div class="wrap nav">
  <a class="brand" href="#home"><span class="mark">N</span><span>NOVA <span>AI</span></span></a>
  <nav id="nav">
   <a href="#home">Accueil</a><a href="#tools">Outils IA</a><a href="#store">Boutique</a><a href="#premium">Premium</a><a href="#contact">Contact</a>
  </nav>
  <a class="btn small" href="#tools">Commencer →</a>
  <button class="menu" id="menu" aria-label="Ouvrir le menu">☰</button>
 </div>
</header>
<main>
<section class="wrap hero" id="home">
 <div>
  <div class="eyebrow">✦ Innovation · Performance · Simplicité</div>
  <h1>Transform Your Business with an <span class="gradient">AI-Powered Solution</span></h1>
  <p class="lead">Découvrez NOVA AI, votre espace numérique pour trouver des idées, créer plus facilement et gagner du temps grâce à des outils intelligents.</p>
  <div class="actions"><a class="btn" href="#tools">Explorer maintenant →</a><a class="btn secondary" href="#features">Découvrir NOVA AI</a></div>
 </div>
 <div class="visual" aria-label="Illustration abstraite futuriste">
  <div class="orb"></div><div class="ring"></div><div class="ring two"></div><div class="ai-core"></div>
  <div class="visual-label">NOVA INTELLIGENCE</div>
 </div>
</section>
<section class="wrap section" id="features">
 <div class="section-head"><div><h2>Everything you need, <span class="grad">in one place.</span></h2><p class="sub">Des ressources numériques simples pour avancer dans tes projets.</p></div></div>
 <div class="cards">
  <article class="card"><div class="ico">✧</div><h3>AI Tools</h3><p>Des outils pratiques pour trouver des idées et structurer tes projets.</p></article>
  <article class="card"><div class="ico">▣</div><h3>Digital Store</h3><p>Des modèles, guides et ressources numériques à consulter.</p></article>
  <article class="card"><div class="ico">➤</div><h3>Productivity</h3><p>Organise ton travail et transforme tes idées en actions.</p></article>
  <article class="card"><div class="ico">⌘</div><h3>Learning</h3><p>Découvre des méthodes et développe de nouvelles compétences.</p></article>
 </div>
</section>
<section class="wrap section" id="tools">
 <div class="section-head"><div><h2>Try our <span class="grad">free tools.</span></h2><p class="sub">Un premier outil de démonstration, utilisable sans compte ni paiement.</p></div><span class="tag">BÊTA · GRATUIT</span></div>
 <div class="tool-layout">
  <div class="toolbox">
   <h3>Générateur d'idées</h3><p class="sub">Choisis un thème et obtiens une piste pour commencer.</p>
   <label for="topic">Ton domaine</label>
   <select id="topic" class="field"><option>Création de contenu</option><option>Études et apprentissage</option><option>Petite entreprise</option><option>Organisation personnelle</option><option>Sport et loisirs</option></select>
   <button class="btn" id="generate" style="margin-top:14px">Générer une idée ✦</button>
  </div>
  <div class="toolbox"><h3>Ton idée apparaît ici</h3><p class="sub">Cette démo fonctionne localement. Elle n'utilise pas encore un véritable modèle d'IA.</p><div class="output" id="result" aria-live="polite">Choisis un domaine puis appuie sur « Générer une idée ».</div></div>
 </div>
 <div class="notice">Prototype : le générateur actuel est une démonstration à règles prédéfinies, pas encore une IA connectée. Une véritable IA nécessitera une intégration technique et pourra entraîner des coûts.</div>
</section>
<section class="wrap section" id="store">
 <div class="section-head"><div><h2>Digital <span class="grad">store.</span></h2><p class="sub">Exemples de ressources que NOVA AI pourrait proposer.</p></div></div>
 <div class="products">
  <article class="product"><div class="cover">▤</div><span class="tag">MODÈLE</span><h3>Organisateur de projet</h3><p class="sub">Un modèle pour planifier les étapes d'une idée.</p><div class="price">À définir</div><button class="btn secondary small" disabled>Disponible bientôt</button></article>
  <article class="product"><div class="cover">✦</div><span class="tag">GUIDE</span><h3>Kit de prompts créatifs</h3><p class="sub">Des exemples de consignes pour mieux utiliser les assistants IA.</p><div class="price">À définir</div><button class="btn secondary small" disabled>Disponible bientôt</button></article>
  <article class="product"><div class="cover">▦</div><span class="tag">PACK</span><h3>Pack productivité</h3><p class="sub">Des fiches simples pour organiser ses tâches.</p><div class="price">À définir</div><button class="btn secondary small" disabled>Disponible bientôt</button></article>
 </div>
 <div class="notice">La boutique est une maquette : aucun paiement ni achat n'est activé. Les produits, prix, conditions de vente et moyens de paiement devront être préparés avant toute commercialisation, avec l'aide d'un parent.</div>
</section>
<section class="wrap section" id="premium">
 <div class="toolbox" style="text-align:center;padding:34px 24px">
  <span class="tag">NOVA PLUS · À VENIR</span><h2 style="margin:12px 0">More possibilities. <span class="grad">One NOVA.</span></h2>
  <p class="sub" style="max-width:650px;margin:0 auto 20px">Des outils supplémentaires et des ressources avancées pourront être proposés plus tard. Nous commencerons par vérifier que les outils gratuits sont vraiment utiles.</p>
  <a class="btn secondary" href="#contact">Suivre le lancement</a>
 </div>
</section>
<section class="wrap section" id="contact">
 <div class="section-head"><div><h2>Stay in <span class="grad">touch.</span></h2><p class="sub">Une question ou une suggestion pour NOVA AI ?</p></div></div>
 <div class="toolbox"><p class="sub">L'espace contact sera activé lorsque l'adresse officielle du projet sera créée. En attendant, note les retours des premiers testeurs directement.</p><a class="btn" href="#home">Retour en haut ↑</a></div>
</section>
</main>
<footer><div class="wrap foot"><div><strong>NOVA AI</strong> · Your digital world, powered by AI.</div><div>Prototype de démonstration · © NOVA AI</div></div></footer>
<script>
const menu=document.getElementById('menu'),nav=document.getElementById('nav');
menu.addEventListener('click',()=>nav.classList.toggle('open'));
nav.querySelectorAll('a').forEach(a=>a.addEventListener('click',()=>nav.classList.remove('open')));
const ideas={
"Création de contenu":["Prépare une série de 5 publications autour d'une question fréquente de ton audience, puis demande à 3 personnes laquelle leur est la plus utile.","Transforme un conseil que tu connais bien en mini-guide illustré d'une page.","Crée un calendrier de contenu sur une semaine avec un thème différent chaque jour."],
"Études et apprentissage":["Crée une fiche de révision qui explique une notion avec un exemple concret et trois questions d'entraînement.","Transforme un chapitre en cartes de mémorisation question-réponse.","Explique une notion difficile en 60 secondes avec un schéma et un exemple."],
"Petite entreprise":["Repère une question que les clients posent souvent et crée une page qui y répond clairement.","Prépare un modèle de devis ou de suivi client simple, puis fais-le tester par un commerçant.","Crée une FAQ courte pour aider les visiteurs à comprendre une offre."],
"Organisation personnelle":["Fais une liste de trois priorités pour la semaine et découpe chacune en petites étapes.","Crée une routine de préparation de 10 minutes pour démarrer une tâche importante.","Regroupe tes tâches par contexte : téléphone, ordinateur, maison ou extérieur."],
"Sport et loisirs":["Crée un carnet pour suivre les séances, les objectifs et les sensations, sans comparer les personnes entre elles.","Prépare un guide débutant qui explique le vocabulaire essentiel d'une activité.","Construis un calendrier d'entraînement ou de pratique avec des jours de récupération."]
};
document.getElementById('generate').addEventListener('click',()=>{
 const topic=document.getElementById('topic').value,arr=ideas[topic],pick=arr[Math.floor(Math.random()*arr.length)];
 document.getElementById('result').textContent=pick;
});
</script>
</body>
</html>
