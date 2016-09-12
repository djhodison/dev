# **O que é WekaPAR?**
A WekaPAR é uma extensão que acrescenta recursos de visualização, filtragem e análise de Regras de Associação geradas a partir da ferramenta de mineração de dados [WEKA](http://www.cs.waikato.ac.nz/ml/weka/).

Esta extensão aprimora as funcionalidades da WEKA, acrescentando recursos de visualização e análise de regras geradas, de forma integrada a ferramenta WEKA, e sem a obrigatoriedade de realizar um processo de exportação e importação dos dados. Esta extensão não modifica a forma como as regras de associação são geradas na WEKA. 

O propósito da WekaPAR é prover ao usuário da ferramenta WEKA um ambiente onde as regras mais interessantes possam ser selecionadas, dado um conjunto de parâmetros estabelecidos pelo usuário, e, ao mesmo tempo que a WekaPAR se integra a WEKA, garante a independência entre a extração de regras de associação pelo algoritmo da WEKA e o pós-processamento dos padrões obtidos.

# **Como obter?**
Para obter a extensão WekaPAR, clique [aqui](https://github.com/).

> * Nota: Para utilizar a extensão WekaPAR, é necessário ter instalada a ferramenta WEKA.
Caso ainda não possua a ferramenta WEKA, clique [aqui](http://www.cs.waikato.ac.nz/ml/weka/downloading.html) para realizar o download.

# **Como instalar?**
Para instalar a extensão WekaPAR na ferramenta WEKA, você pode [assistir](https://github.com/) ou ler as instruções abaixo.

> * Nota: Não é necessário descompactar a extensão WekaPAR para efetuar o procedimento de instalação.

## **Manual de Instalação:**
> * Abra a ferramenta WEKA, clique em 'Tools' e depois em 'Package manager'.
> * Clique em 'File/URL' no canto superior direito.
> * Clique em 'Browse', localize e selecione a extensão WekaPAR. Em seguida, clique em 'OK'.
> * Você deverá visualizar um aviso alertando a necessidade de reiniciar a ferramenta WEKA. 
> * Após reiniciar a ferramenta WEKA, clique em 'Explorer'.
> * Você deverá visualizar uma nova aba chamada 'Postprocess associations'.
> * Parabéns! Você instalou a extensão WekaPAR com sucesso.

# **Como utilizar?**
Para utilizar a extensão WekaPAR, você pode [assistir](https://github.com/) ou ler as instruções abaixo.

## **Manual de Utilização:**
> * Obtenha regras de associação normalmente, através da aba 'Associate'. Para obter instruções mais detalhadas sobre procedimentos anteriores a este, recomendamos assistir nosso [vídeo](https://github.com/) contendo instruções detalhadas.
> * Marque a opção 'Store output for visualization' e clique em 'Start' para obter as regras de associação.
> * Em 'Result list', abra o menu de contexto, clicando com o botão direito do mouse, sobre o item desejado.
> * Selecone 'Plugins' e depois 'View in postprocess tab'.

> * ### Na aba **'Postprocess associations'** você irá encontrar:
> * **Command bar:** Contendo opções para salvar as regras apresentadas em arquivo, abrir novamente o conjunto de regras e exportá-lo no formato CSV.  A extensão WekaPAR permite que as regras extraídas sejam salvas em arquivo e possam ser carregadas novamente sem a necessidade de executar novamente o algoritmo de mineração de regras de associação. No entanto, a contribuição desta funcionalidade limita-se a etapa de pós-processamento. Uma vez que exista a necessidade de refazer atividades relacionadas a outras etapas, como a seleção de dados, o algoritmo deverá ser executado novamente para gerar novas regras.

> * **Filter for rules:**
> * **Minimun values for metrics:**
> * **Rules:**
> * **Status:**

# **Qual a compatibilidade?**
A extensão WekaPAR funciona a partir da versão 3.7.8 da ferramenta WEKA. Entretanto, aconselhamos que os usuários estejam com a ferramenta WEKA em sua versão 3.8.0 ou superior.

Até a versão 3.7.13 existia um bug que, em alguns casos, poderia gerar valores ligeiramente diferentes para as medidas de interesse, quando comparados com a saída original. Este problema foi reportado na lista de usuários da WEKA e foi corrigido, mas essa correção foi disponibilizada apenas na versão 3.8.0. 

Portanto, esta é a versão na qual o plugin pode ser utilizado sem o bug.

# **Estou com problemas. O que devo fazer?**
Para problemas com o download da extensão WekaPAR, clique [aqui](https://github.com/).

Para problemas com a instalação da extensão WekaPAR, clique [aqui](https://github.com/).

Para problemas com o valores divergentes, clique [aqui](https://github.com/).

Você também pode entrar com contato direto com a equipe WekaPAR por meio deste [link](https://github.com/).

# **Como contribuir com a WekaPAR?**
Para contribuir com a extensão WekaPAR, leia:


