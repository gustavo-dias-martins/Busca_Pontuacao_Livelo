<h1> Pontuação dos Parceiros Livelo </h1>
<p>O projeto é um código desenvolvido em Python para automatizar a busca de algumas informações dos parceiros da Livelo. Entre os parceiros que podemos encontrar na Livelo temos: Movida, Americanas, Amazon, Riachuelo entre outras. As informações que o código retorna são:</p>
<p>- Pontuação</p>
<p>- Regulamento para aquela promoção válida</p>
<p>- Link para a promoção</p>

<h2> Bibliotecas Utilizadas </h2>
<p>- Selenium</p>
<p>- Time</p>
<p>- Tqdm</p>
<p>- Pandas</p>

<h2> Como funciona? </h2>
<p>Utilizando o Selenium podemos simular a navegação pelo site até chegar na página dos parceiros. No fim de cada ciclo incluímos as informações encontradas em um DataFrame do Pandas, o parceiro que não for encontrado na procura o código pula e não adiciona no Dataframe.</p> 
