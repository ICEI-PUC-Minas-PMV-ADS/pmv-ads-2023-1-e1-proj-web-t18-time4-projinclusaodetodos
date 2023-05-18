<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 10px;
  background: #f1f1f1;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  text-align: center;
  background: white;
}

.header h1 {
  font-size: 50px;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: left;
  width: 75%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #f1f1f1;
  padding-left: 20px;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}

/* Clear floats after the columns */
.row::after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .topnav a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>EDUCAÇÃO COM INCLUSÃO</h1>
  <p>Aqui, a educação é para todos!</p>
</div>

<div class="topnav">
  <a href="#">By My Eyes </a>
  <a href="#">Seeing AI </a>
  <a href="#">Hand Talk </a>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>O direito de acesso e permanência da pessoa com deficiência no ensino superior: </h2>
      <h5>Publicado por Flávio Adriano, em Out 14, 2021</h5>
      <div class="fakeimage" style="height:200px;">https://img.imageboss.me/revista-cdn/cdn/31053/44968eacfc2afdab33f81630b16692975cee5622.jpg?1598537358</div>
      <p> “Cuidados Sem Limites” </p>
      <p>O Estatuto da Pessoa com Deficiência, instituído pela Lei nº 13.146, também conhecida como Lei Brasileira de Inclusão da Pessoa com Deficiência, de 6 de julho de 2015, define como pessoa com deficiência (PcD) aquele que possui comprometimento de natureza física, mental, intelectual ou sensorial, a longo prazo, capazes de dificultar sua participação na sociedade de forma equivalente aos demais indivíduos. 

O Instituto Brasileiro de Geografia e Estatística (IBGE), por meio da Pesquisa Nacional de Saúde (PNS) de 2019, aponta que 8,4% da população brasileira acima de 2 anos – o que representa 17,3 milhões de pessoas – têm algum tipo de deficiência. Quase metade dessa parcela (49,4%) é de idosos. 

Os resultados da PNS de 2019 mostraram diferenças relevantes entre o nível de instrução das pessoas a partir de 18 anos de idade com deficiência em comparação com as sem deficiência. Quase 68% (aproximadamente 12 milhões de pessoas) da população com deficiência não têm instrução ou possui o ensino fundamental incompleto, enquanto para as pessoas sem nenhuma das deficiências investigadas a taxa é de 30,9%. </p>
    </div>
    <div class="card">
      <h2>Número de estudantes com deficiência cresce no Ensino Superior, mas permanência esbarra na falta de acessibilidade</h2>
      <h5> Por Giovana Murça, Aug 27, 2020</h5>
      <div class="fakeimg" style="height:200px;">https://img.imageboss.me/revista-cdn/cdn/31058/da23d9348fd7140dc05ee55627d1131ae348e1ca.jpg?1598538373</div>
      <p>Os impactos da inclusão</p>
      <p>De 2017 para 2018, o número de estudantes com deficiência matriculados na universidade por meio da reserva de vagas cresceu mais de 70%, de acordo com o Censo Superior da Educação. O número de matriculados PcD com cotas passou de 2.962 (0,04% do total de matriculados), em 2017, para 5.053 (0,06% do total de matriculados), em 2018.

Apesar do crescimento, as pessoas com deficiência (PcD) ainda representam apenas 0,52% do total de matriculados em cursos de graduação do Ensino Superior, com 43.633 alunos em 2018.</p>
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>Sobre mim:</h2>
      <p>Um grupo interessado em criar sites e aplicativos que permitam a inclusão de PcDs, acessibilidade por meio de aplicativos, e acima de tudo, o aumento no número de pessoas com limitações com ensino superior.</p>
    </div>
    <div class="card">
      <h3>Principais Títulos:</h3>
      <div class="fakeimg"><p>https://img.imageboss.me/revista-cdn/cdn/31051/40c6453902f6c6a74d68f3a8ab46dbdb5f3edc5b.png?</p></div>
      <div class="fakeimg"><p>https://querobolsa.com.br/revista/numero-de-estudantes-com-deficiencia-cresce-no-ensino-superior-mas-permanencia-esbarra-na-falta-de-acessibilidade</p></div>
    </div>
    <div class="card">
      <h3>Siga-me nas redes:</h3>
      <p>@educacaoparatodos</p>
    </div>
  </div>
</div>

<div class="footer">
  <h2>CONHEÇA NOSSOS OUTROS BLOGS:
Academia Tech |
Academia Health |
Faz Direito</h2>
</div>

</body>
</html>
