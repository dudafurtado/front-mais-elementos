# Conhecendo mais elementos

**Elemento de linha** = textos que permanecem naquela linha.  
**Elemento de bloco** = quebra linha e gera uma separação de conteúdo.

-     <div><div/>  
Não tem um significado especial, mas pode ser entendido como uma divisão.  
Possui uma quebra de linha.  
É permitido colocar qualquer tag dentro.

-     <span><span/>  
É um elemento de linha, então não gera espaço para baixo de outro elemento.

-     <header><header/>  
Cabeçalho com elemnetos tipo: logo do site, nome do documento, informações chaves de seo, navegações, lista de links com fontes e estilos da página.

-     <nav><nav/> 
Elemento com valor de navegação pelo site, cobre tag de listagem ou de botão, por exemplo.

-     <aside><aside/>  
Guia ou card no canto direito ou esquerdo da página que não obrigatóriamente tem referência com o conteúdo principal da main.

-     <main><main/>  
Caracteriza o conteúdo principal da página, aquele de maior destaque e atenção pelo usuário.  
!! Não é recomendado usar mais de uma tag main por documento. 
  
-     <article><article/>
É destinado a ser distribuído de forma independente ou reutilizável. Conteúdo independente de documento, página, aplicação ou site.  
  É recomendado usar dentro dele um *<heading><heading/>* , *<footer><footer/>* e um *<time><time/>* para data e hora de publicação.
!! É possível colocar um conjunto de article dentro de uma section
  
-     <section><section/>
Uma sessão da página, ao qual, pode receber qualquer tag.
É comum ser um agregado de tags juntas.
!! É possível colocar um conjunto de section dentro de uma article.
  
-     <footer><footer/>
Rodapé.  
Possui mídias sociais, contato, termos de usabilidade do site e links no geração.  
Possui navegação, por isso o elemento nav.
  
-     <p><p/>  
**Propriedades:**  
  *hidden* --> vai esconder o valor presente dentro da tag e a própria tag no geral;  
  *title=""* --> ao deslizar o mouse por cima do elemento ele reflete uma mensagem adicional na tela, escrita dentro da propriedade;  
  *dir* --> especifica de antemão se esse texto deve se posicionar na direita ou na esquerda;   
  *lang* --> linguagem do texto dentro da tag.
  
-     <img><img/>  
É considerado um elemento de linha.
**Propriedades:**  
  *src=""* --> caminho da imagem;  
  *alt=""* --> descrição de acessibilidade sobre os detalhes da imagem.
  
-     <a><a/>  
  Âncora, hiper link
**Propriedades:**  
*href=""* --> após o clique, redireciona o usuário para a url de referência.
  
-     <button><button/>  
**Propriedades:**  
*value=""* --> o que esse botão faz ao ser clicado, qual funcionalidade foi atribuida a tag.
  
-     <input><input/>  
**Propriedades:**  
*value=""* --> o que esse input faz ao ser clicado, a qual local os dados inseridos irão, qual finalidade elas tem. possivelmente banco de dados.
  
-     <option><option/>  
Cada tag é uma opção referente a o tipo de input seletor.
  
  // ACESSIBILIDADE PARA USUÁRIOS DE DIFICULDADE VISUAL
  
-     <strong><strong/>  
Importância para o conteúdo, gera atenção para a informação.  
Conteúdo em negrito.
  
-     <b><b/>  
Não gera urgência, mas sim um destaque especifico.  
  
-     <i><i/>   
Deixa a fonte no estilo italico.  
Para interlocução, o tom de voz se diferencia das outras tags, gerando uma emoção específica.  
  
-     <em><em/>   
Representa enfâse e foco.  
  
 id --> identificador único para diferenciar elementos da tela. é o mais importante na hierarquia;
 class --> classifica a tag, sendo usado frequentemente. 
  
###### tags: `módulo 1` `front-end` `HTML`
