<h1>Introdução e Descrição</h1>
<p>Esse é um mini projeto criado para estudar e praticar algumas bibliotecas do python, como Pandas, Requests, BeautifulSoup, OS. Adicionado os dados obtidos em uma tabela já existente. Ressaltando que esse projeto não possui objetivo algum de intenção de lucro, apenas objetivo de aprender.<br>
Foi utilizado como fonte de recolhimento de dados o site www.analisedeacoes.com, site que expõe de forma gratuita informações sobre empresas listadas na bolsa. Como dito as bibliotecas Pandas, Requests, BeautifilSoup, OS  e Datatime, foram usadas.<br>
Basicamente o programa funciona pegando as informações de Tags HTML(Cotação, P/L, P/VP, DY, ROIC, ROE, entre outras) e armazenando em linhas da tabela, depois salvando em uma planilha que foi previamente carregada. Assim é por padrão a planilha, com somente uma coluna:<br>
  DATA |PAPEL |COTACAO |DY |P/L |P/VP |LPA |VPA |PSR |P/EBIT |EV/EBIT |EV/EBITDA |ROE |ROIC<br>
Como todos os indicadores estão relacionados a cada papel, que está relacionada a uma data, esta planilha pode ser utilizada para fazer diferentes tipos de análises de ações.</p>
<h2>Problemas</h2>
<p>Devido a como foi construído o html da página onde estão sendo pegas as informações, em algumas ações há Tags que estão faltando, atrapalhando a obtenção de dados. Quando um dado esta claramente posicionado de forma errada na tabela, é preenchido com “---“, linhas que possuem esse preenchimento na tabela, possuem uma falta de precisão e isso deve ser levado em consideração.<br>
Estou utilizando o método “.append()” da biblioteca pandas, esse método não está disponível por muito tempo./<p>

<h2>Conclusão</h2>

<p>O desenvolvimento foi satisfatório, há problemas, como já explicado, que podem ser resolvidos, há a possibilidade de usar melhor as variaveis e funções, mas talvez futuramente melhore o código.</p> 
