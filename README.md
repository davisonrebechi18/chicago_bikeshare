# chicago_bikeshare
## Resumo: 
<p>Explorar os dados relacionados aos sistemas de compartilhamento de bicicletas nas três maiores cidades dos Estados Unidos: Chicago, Nova Iorque e Washington. Você escreverá um código para importar dados e responder a perguntas interessantes sobre eles, por meio da computação de estatísticas descritivas.
</p>
<h2>Descrição:</h2>
<p>Dados sobre compartilhamento de bicicletas na última década, os sistemas de compartilhamento de bicicletas têm crescido em número e popularidade nas cidades de todo o mundo. Sistemas de compartilhamento de bicicletas permitem que os usuários aluguem bicicletas por um período curtíssimo, por um preço específico. Isso permite que pessoas retirem uma bicicleta do ponto A e a devolvam no ponto B, embora também possam devolvê-la no mesmo local, caso queiram apenas sair para um passeio. Independentemente disso, cada bicicleta pode servir vários usuários por dia.
</p>
<p>Graças à ascensão das tecnologias de informação, é fácil para um usuário acessar uma estação dentro do sistema para desbloquear ou devolver as bicicletas. Essas tecnologias também fornecem uma riqueza de dados que podem ser utilizados para explorar como esses sistemas de compartilhamento de bicicletas são usados.
</p>
<p>Neste projeto, foi usado os dados fornecidos pelo Motivate, um provedor de sistema de bicicletas compartilhadas para diversas grandes cidades dos Estados Unidos, para descobrir os padrões de uso do compartilhamento de bicicletas. Você analisará o uso do sistema de uma das maiores cidades dos Estados Unidos: Chicago.</p>

## Os conjuntos de dados:
<p>Os dados para os primeiros seis meses de 2017 são fornecidos. O arquivo de dados contêm seis (6) colunas principais:</p>

<ul>
  <li>Horário de início (ex., 2017-01-01 00:07:57)</li>
  <li>Horário de término (ex., 2017-01-01 00:20:53)</li>
  <li>Duração da viagem (em segundos, ex., 776)</li>
  <li>Estação inicial (ex., Broadway & Barry Avenue)</li>
  <li>Estação final (ex., Sedgwick St & do North Ave)</li>
  <li>Tipo de usuário (assinante ou cliente)</li>
  <li>Gênero do usuário</li>
  <li>Ano de nascimento do usuário</li>
</ul>

<p>Os arquivos originais podem ser acessados aqui: https://s3.amazonaws.com/video.udacity-data.com/topher/2018/September/5ba00ce4_chicago-bikeshare-pt/chicago-bikeshare-pt.zip - o dataset tinha mais colunas, e elas diferiam em formato em muitos casos. Alguns processos de data wrangling foram realizados para condensar esses arquivos nas seis colunas principais citadas acima, para simplificar a análise e a avaliação das habilidades em Python. 
</p>

