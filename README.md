<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width">
	<title>repl.it</title>
	<link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
	<script src="script.js">

	</script>
	<!--div itemscope itemtype="http://schema.org/Product">
              <img itemprop="image" src="/image-book.jpg" alt="Imagem do Livro"/>
              </br>
              <h3 class="titulo" itemprop="name">O Iluminado</3>

              <div itemprop="offers" itemscope itemtype="http://schema.org/AggregateOffer">
              <div itemprop="aggregateRating" itemscope itemtype="http://schema.org/AggregateRating"-->
	<div itemscope itemtype="http://schema.org/ItemList">
		<span itemprop="numberOfItems">Número de Itens: 500</span>
    </br>
    <div class="descricao" itemprop="itemListElement" itemscope itemtype="http://schema.org/Product">
      <div class="descricao box">
        <img class="descricao imagem" alt="Imagem do Produto" itemprop="image" src="image-book.jpg">
        <h3 class="descricao texto" itemprop="name">O Iluminado</h3>
        <span class="descricao texto" itemprop="author">Stephen King</span></br>
        <img class="descricao rating" alt="Imagem do rating" src="rating5.jpg"></br>
        <span itemprop="ratingValue" value="5></span></br>
        <div itemprop="offers" itemscope itemtype="http://schema.org/Offer">
        <span class="descricao preco" itemprop="price">R$15.90</span></br>
        <a class="descricao detalhes" itemprop="url" href="http://localhost:8080/detalhe.html">Mais detalhes...</a>
        </div>
      </div>
    </div>
  </body>
</html>
