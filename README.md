# pagina-da-web<header>
  <h1>Blog sobre TDAH</h1>
  <p>Aprendendo mais sobre atenção, organização e rotina</p>
</header>

<nav>
  <a href="#sobre">Sobre</a>
  <a href="#galeria">Galeria</a>
  <a href="#curiosidades">Curiosidades</a>
  <a href="#quiz">Quiz</a>
</nav>

<main>

  <section id="sobre">
    <h2>O que é TDAH?</h2>

    <img
      src="https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=1000&q=80"
      alt="Estudante estudando">

    <p>
      O TDAH significa Transtorno do Déficit de Atenção e Hiperatividade.
      Ele pode influenciar a concentração, a organização e o controle dos impulsos.
    </p>

    <p>
      Cada pessoa é diferente e pode desenvolver estratégias para aprender e se organizar melhor.
    </p>
  </section>

  <section id="galeria">

    <h2>Galeria</h2>

    <div class="galeria">

      <img src="https://images.unsplash.com/photo-1513258496099-48168024aec0?auto=format&fit=crop&w=60header>
  <h1>Blog sobre TDAH</h1>
  <p>Aprendendo mais sobre atenção, organização e rotina</p>
</header>

<nav>
  <a href="#sobre">Sobre</a>
  <a href="#galeria">Galeria</a>
  <a href="#curiosidades">Curiosidades</a>
  <a href="#quiz">Quiz</a>
</nav>

<main>

  <section id="sobre">
    <h2>O que é TDAH?</h2>

    <img
      src="https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=1000&q=80"
      alt="Estudante estu0&q=80">

      <img src="https://images.unsplash.com/photo-1503676382389-4809596d5290?auto=format&fit=crop&w=600&q=80">

      <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=600&q=80">

    </div>

  </section>

  <section id="curiosidades">

    <h2>Curiosidades</h2>

    <div class="card">
      <h3>📚 Organização ajuda</h3>
      <p>Agendas e listas facilitam o dia a dia.</p>
    </div>

    <div class="card">
      <h3>⏰ Rotinas são importantes</h3>
      <p>Horários definidos ajudam na realização das tarefas.</p>
    </div>

    <div class="card">
      <h3>🎯 Uma tarefa por vez</h3>
      <p>Dividir atividades grandes em etapas pode ajudar.</p>
    </div>

  </section>

  <section id="quiz">

    <h2>Quiz</h2>

    <p>O TDAH pode afetar a atenção?</p>

    <button onclick="acertou()">
      Sim
    </button>

    <button onclick="errou()">
      Não
    </button>

    <p id="resultadoQuiz"></p>

  </section>

</main>

<footer>
  <p>Projeto Escolar - Blog sobre TDAH</p>
</footer>
*ground:4a90e2;
  color:{
  margin:0;
  padding:0
    box-sizing:border-box;
}
body{
  font-family-:Arial, sans-serfil;
  background:#f0f4f8;
  color:#333
}

header{
  backwhite;  color:{
  margin:0;
  padding:0
  text-*align:center;
  padding:30px;
}

nav{
 background:#2f6fb3;
  padding:15px;
  text-align:center;
}

nav a{
 color:white;
  text-decoration:none;
  margin:15px;
  font-weight:bold;
}

nav a:hover{
  text-decoration:underline;
}

main{
  max-width:1000px;
  margin:auto;
  padding:20px;
}

section{
  margin-botton:40px;
}

h2{
  color:#2f6fb3;
  margin-bottom:15px;
}

section img{
  width:100%;
  border-radius:10px;
  margin-bottom:15px;
}

.galeria{
  display:flex;
  gap:15px;
  flex-wrap:wrap;
}

.galeria img{
  width:300px;
  border-radius:10px;
}

.card{
  background:white;
  padding:15px;
  margin-top:15px;
  border-radius:10px;
  box-shadow:02px 8px rgba(0,0,0,0.1);
}

button{
  padding:10px 20px;
  margin:10px;
  border:none;
  border-radius:5px;
  background:#4a90e2;
  color:white;
  curson:pointer;
}

button:hover{
  background:#2f6fb3;
}

#resultadoQuiz{
  margin-top:15px;
  font-weight:bold;
}

footer{
  background:#4a90e2;
  color:white;
  text-align:center;
  padding:20px;
}
function acertou(){
  
  document.getElementByld('resultadoQuiz').innerHTML=
"https://emojiterra.com/pt/marca-de-verificacao/Muito bem! A resposta esta correta.";
  
}

function errou(){
  document.getElementByld("resultadoQuiz").innerHTML=
    "https://emojiterra.com/pt/x-vermelho/ Tente novamente. O TDAH pode afetar a atenção";
  
}
