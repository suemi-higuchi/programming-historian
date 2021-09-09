Parabéns ao Ian que fez um ótimo trabalho! A lição é bastante longa e a adaptação dos exemplos com uso de dados do Gapminder ficou excelente. Testei todo o código e abaixo estão minhas sugestões.  

* Sobre o título: difícil traduzir wrangling, mas ao invés de "transformação" que tal "organização" ou "controle"? Ficaria algo como "Manipulação e controle de dados no R"?  

* Não há ainda a tradução do resumo. Minha sugestão: "Esta lição explora como os investigadores podem tornar seus dados ordenados, entender os pacotes R para manipular dados e conduzir análises básicas de dados."

* É preciso rever as URLs das imagens.

* Eu havia feito a edição da revisão diretamente no arquivo markdown do Ian. Aqui está ele, caso facilite na hora de entender os pontos que coloquei, principalmente as notas extras de rodapé: https://github.com/suemi-higuchi/programming-historian/blob/main/lesson_revised_1.md

#### Na seção "Premissas":
* Linha 20: substituir "Premissas" por "Requisitos";
* Linha 23: substituir "Esta lição considera premissas básicas acerca do seu" por "Nesta lição assumimos que você possui algum"; "Se você" por "Se ainda"; "eu sugiro que complete-a primeiro" por "sugerimos que o faça primeiro"; "recomendo dar uma olhada nos" por "recomendamos os";

#### Na seção "Objetivos da lição":
* Linha 30: excluir o auxiliar "vai";
* Linha 32: Substituir "Saber manipular dados para organizá-los no formato “tidy” e entender porque" por "Saberá como tornar seus dados bem ordenados (*tidy*) e entenderá por que";
* Linha 33: Substituir "Entender" por "Terá assimilado";
* Linha 34: Substituir "Se familiarizar" por "Estará familiarizado"; "operador pipe" por "operador *pipe* `%>%`";  "obsevar como ele te auxiliará" por "verá como ele pode auxiliar";
* Linha 35: Substituir "Aprender a trabalhar com exemplos básicos de manipulação de dados, a fim de gerar experiência com análise de dados exploratória" por "Terá ganho experiência com análise exploratória de dados através de exemplos básicos de manipulação de dados";

#### Na seção "Introdução":
* Linha 40: Substituir "por aí" por "disponíveis em todo lugar"; excluir "um"; substituir "preferível" por "adequado"; "da forma como foi" por "conforme";
* Linha 45: "registro" por "unidade de observação"; todos os "deve estar" por "está";
* Linha 49: '"permite utilizar uma série de ferramentas padrões para a limpeza dos dados e solução dos" por "fornece um esquema padrão e um conjunto de soluções para lidar com alguns dos"; "bases de dados “bagunçadas”:" por "datasets “mal-arranjados”, como por exemplo:";
* Linha 51: "das" por "de"; "não como" por "ao invés de"; "nome de variável" por "nomes de variáveis";
* Linha 54: "Vários registros de categorias diferentes" por "Unidades de observação de diferentes categorias";
* Linha 57: "O mais importante:" por "Talvez o mais importante seja que"; 'desenhadas especificamente para trabalhar com dados organizados, "tidy"' por 'concebidos para trabalhar especificamente com dados neste formato "tidy"'; 'nossos inputs e outputs são "tidy"' por "os dados de entrada e de saída estão bem organizados"; "ferramental" por "conjunto de ferramentas"; "problema" por "questões"; "bases de dados" por "*datasets*"; "conforme nossa necessidade" por "conforme considerarmos mais adequado";
* Linha 63: Sugiro incluir esta nota explicativa para a Gramática dos Gráficos: "[^1]: A lição original faz referência ao livro “[The Grammar of Graphics](https://www.springer.com/us/book/9780387245447)” (2005) de Wilkinson]";
* Linha 64: "fácil" por "fáceis";
* Linha 66: 'Você deve instalar, se ainda não instalou, e carregar o "tidyverse"' por 'Você deve instalar o "tidyverse", se ainda não o fez, e carregá-lo'; "que você" por "de que"; "em suas respectivas plataformas" por "compatíveis com o seu sistema operacional";
* Linha 69: "rodar" por "executá-lo"; 
* Linha 71: "Instala e carrega a biblioteca tidyverse"; 
* Linha 72: "Não se preocupe caso demore um pouco";

#### Na seção "Um exemplo do dplyr em ação"
* Linha 80: "Vejamos um exemplo de como o dplyr pode auxiliar historiadores.  Vamos utilizar o pacote "dados"[^2] e importar alguns indicadores socioeconômicos de países entre 1952 e 2007.";
* Linha 80: Sugiro incluir esta nota explicativa para o pacote *dados*: "[^2]:O pacote "dados" disponibiliza a tradução de conjuntos de dados originalmente em inglês encontrados em outros pacotes de R. Está disponível em https://github.com/cienciadedatos/dados";
* Linha 82: Antes das instruções, sugiro incluir "O pacote "remotes" permite a instalação de pacotes R a partir de repositórios remotos, incluindo o GitHub, como é o caso de "dados".";
* Linha 90: "Para obter a base de dados que vamos utilizar, através do" por "Para termos acesso ao *dataset* "dados_gapminder" que se encontra no";
* Linha 92: "Designa a base de dados" por "Atribui o *dataset*"; 
* Linha 95: Como se trata de um dataset diferente do da lição original, sugiro incluir no início do parágrafo: "Os dados [Gapminder](https://www.gapminder.org/) contêm a progressão de países ao longo do tempo, observando as estatísticas de alguns índices.";
* Linha 95: Substituir "base" por "*dataset*";
* Linha 97: "Vamos utilizar" por "Para isso utilizaremos'; "afim de analisar informações somente" por "que contenham apenas informação"; "a informação produzida" por "tais dados"; "poder do" por "que é possível fazer com o";
* Linha 99: Excluir "a base de dados para conter apenas";
* Linha 112: "novos questionamentos" por "questões similares"; excluir ", mas";
* Linha 115: Excluir "a base de dados para conter apenas";
* Linha 128: "Fazer rápidas mudanças em nosso código e analisar novamente" por "Promover mudanças rápidas no código e reanalisar"; "melhores questionamentos" por "questões sobre eles"; "de saber quando se aprofundar mais em um assunto e quando voltar atrás, e este é um aspecto onde o R se sobressai.";

#### Na seção Operador Pipe
* Linha 133: "que faz parte do" por "está incluída no"; ""A Traição das Imagens", uma pintura de um cachimbo com a frase em francês: "isto não é um cachimbo"" por "["A Traição das Imagens"](https://www.renemagritte.org/the-treachery-of-images.jsp), que mostra um cachimbo com a frase "isto não é um cachimbo" (*ceci n'est pas une pipe*, em francês);
* Linha 135: Substituir por "permite que você passe o que está à sua esquerda como a primeira variável em uma função especificada à sua direita. Embora possa parecer estranho no início, uma vez que você aprenda a usar o *pipe* descobrirá que ele torna seu código mais legível, evitando instruções aninhadas. Não se preocupe se estiver um pouco confuso por agora. Tudo ficará mais claro à medida que observarmos os exemplos.";
* Linha 137: "admitir hipoteticamente" por "dizer"; "afim de obter uma" por "antes de calcular a"; "medida válida" por "medição útil"; "ilegível rapidamente" por "difícil de ler";
* Linha 143: Substituir por "Veja que com tantos comandos aninhados fica difícil lembrar de quantos parênteses você precisa no final, tornando o código complicado de ler. Para atenuar esse problema, algumas pessoas criam vetores temporários entre cada chamada de função.";
* Linha 163: "pode rapidamente bagunçar" por "pode se tornar confuso";
* Linha 180: "tabelas" por "*data frames*"; 
* Linha 191: Como isso já foi explicado anteriormente, excluir a frase "contendo informações dos avanços dos indicadores socioeconômicos, ao longo dos anos, de vários países. Vamos olhar mais uma vez nossos dados:";
* Linha 212: "base de dados" e "base" por "*dataset*";    

#### Seção O que é dplyr
* Linha 217: Substituir por "também é parte do tidyverse, fornecendo funções para manipulação e tranformação dos dados. Porque estamos mantendo nossos dados bem organizados, precisaremos apenas de um pequeno conjunto de ferramentas para explorá-los. Em comparação com o pacote básico do R, usando o dplyr nosso código fica geralmente mais rápido, e há a garantia de que os dados resultantes (*output*) estarão bem ordenados uma vez que os dados de entrada (*input*) também estarão."; substituir "desses verbos" por "dessas funções";
* Linha 222: Excluir "o banco de dados"; substituir "durante" por "para"; "base de dados" por "*data frame*";
* Linha 265: "Pode utilizar, de outro modo," por "Podemos usar";
* Linha 287: "requisitos lógicos" por "um teste de requisito";
* Linha 329: "Na verdade" por "Em vez disso"; "base de dados" por "*data frame*";
* Linha 334: "tibble" por "tabela";
* Linha 354: "base de dados" por "conjunto de dados";
* Linha 376: Substituir por "A última função do dplyr que veremos é a `summarise()`, usada geralmente para criar uma tabela contendo dados estatísticos resumidos que podemos plotar.";
* Linha 376: "base" por "conjunto de dados";

#### Seção Conclusão
* Linha 416: "No futuro" por "Além disso".
