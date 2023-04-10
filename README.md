<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RECEITAS</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
  <style>
    *{
      padding: 0px;
      margin: 0px;
    }
    body{
      background-color: lightsalmon;
    }
    h1,h2{
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .card{
      background-color: lightgoldenrodyellow;
      padding: 20px;
      width: 100px;
      height: 700px;
    }
    footer{
      background-color: black;
      color: white;
      display: flex ;
      justify-content: center;
      align-items: center;
      height: 5vh;
      position: absolute;
      width: 100%;
    }
  </style>
</head>
<body>
  <img src="1_21_180314024352_adesivo-de-parede-logo-restaurante-faca-colher-e-garfo.png" class="rounded mx-auto d-block" alt="Logo">

  <h1>
    Receitas da Tia Jurema
  </h1>

  <h2>
    Bem-Vindo(a), ao site da Tia Jurema.
  </h2>
  <h2>
    Conheça deliciosas receitas para o dia a dia.
  </h2>

  <div class="card-group">
    <div class="card">
      <img class="card-img-top" src="gnFzMJfBHRqekdUuwafqfTYTOdVj1qMbJxS59dzG.webp" alt="Arroz de Couve-Flor" width="100px" height="300px">
      <div class="card-body">
        <h3 class="card-title">Arroz de Couve-Flor</h3>
        <p class="card-text">. Arroz</p>
        <p class="card-text">. Couve-Flor</p>
        <p class="card-text">. Cebola Média</p>
        <p class="card-text">. Azeite</p>
      </div>
      <div class="card-footer">
        <p>Deixe a couve-flor picada. Adicione os ingredientes e refogue bem. Adicione sal, tampe a panela e deixe cozinha.</p>
      </div>
    </div>
    <div class="card">
      <img class="card-img-top" src="bolo-de-cafe-camila-dutra.webp" alt="Bolo de Café" width="100px" height="300px">
      <div class="card-body">
        <h3 class="card-title">Bolo de Café</h3>
        <p class="card=text">. Farinha de Trigo</p>        
        <p class="card=text">. Açúcar</p>
        <p class="card=text">. Café Coado</p>
        <p class="card=text">. Cocolate em Pó</p>
        <p class="card=text">. Ovos</p>
      </div>
      <div class="card-footer">
        <p>Bata o açúcar, as gemas e o café. Adicione farinha e chocolate e mexa bem. Bata as claras e junte à mistura.</p>
      </div>
    </div>
    <div class="card">
      <img class="card-img-top" src="bcab5be00f2765a0d799cefcdeef33a1.jpg" alt="Coxinha de Brigadeiro" width="100px" height="300px">
      <div class="card-body">
        <h3 class="card-title">Coxinha de brigadeiro</h3>
        <p class="card-text">. Leite Condençado</p>
        <p class="card-text">. Chocolate em Pó</p>
        <p class="card-text">. Manteiga</p>
        <p class="card-text">. Morango</p>
        <p class="card-text">. Chocolate Granulado</p>
      </div>
      <div class="card-footer">
        <p>Junte o leite condençado, chocolate em pó e manteiga. Aqueça no fogo baixo. Envova os morangos e passe no granulado.</p>
      </div>
    </div>
  </div>

  <form>
    <h2>Efetue seu Cadastro</h2>
    <div class="form-row">
      <div class="form-group col-md-6">
        <label for="inputName">Nome</label>
        <input type="name" class="form-control" id="inputName">
      </div>
      <div class="form-group col-md-6">
        <label for="inputeEmail4">Email</label>
        <input type="email" class="form-control" id="inputeEmail4">
      </div>
      <div class="form-group col-md-2">
        <label for="inputCEP">CEP</label>
        <input type="text" class="form-control" id="inputCEP">
      </div>
      <div class="form-group">
        <label for="inputAddress">Rua</label>
        <input type="text" class="form-control" id="inputAddress">
      </div>
      <div class="form-row">
        <div class="form-group col-md-5">
          <label for="inputCity">Cidade</label>
          <input type="text" class="form-control" id="inputCity">
        </div>
        <div class="form-group col-md-2">
          <label for="inputEstado">UF</label>
          <input type="text" class="form-control" id="inputEstado">
        </div>
      </div>
    </div>
    <button type="button" class="btn btn-dark">Cadastro</button>
  </form>

  <footer>@Jurema</footer>

  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
</body>
</html>
