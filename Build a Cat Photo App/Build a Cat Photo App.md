# Construa um Aplicativo de Foto de Gatos
HTML significa Linguagem de Marcação de Hyper Texto e ele representa o conteúdo e estrutura de uma página web.
Neste seminário, você irá aprender a trabalhar com elementos básicos de HTML que são cabeçalhos, parágrafos, imagens, links e listas.

## Passo 1
Neste oficina, você irá continuar trabalhando com elementos báscico de HTML como cabeçalhos, parágrafos e listas para construir um aplicativo de foto de gotos.

Comece a oficina adicionando um elemento h1 com o texto "CatPhotoApp".

## Passo 2
Abaixo do elemento h1, adicione um elemento h2 com este texto: "Cat Photos"

## Passo 3
Crie um elemento p abaixo do seu elemento h2 e dê a ele o seguinte texto: "Everyone loves cute cats online!"

## Passo 4
Comentário permite você deixar mensagens sem que afete a exibição no navegador. Além disso, é permitido você realizar programação inativa. Um comentário em HTML com com <!--, contains any number of lines of text, and ends with -->.

Aqui está um exemplo de um comentário com o TODO: Remove h1:

### Código de Exemplo
<!-- TODO: Remove h1 -->
Adicione um comentário sobre o elemento p com este texto:

TODO: Add link to cat photos

## Passo 5
HTML5 tem alguns elementos que identificam diferentes áreas do conteúdo. Esses elementos tornam seu HTML mais fácil de ler e ajudam na otimização dos motores de busca (SEO) e acessibilidade.

O elemento main é usado para representar o conteúdo principal do corpo de um documento HTML. O conteúdo dentro do elemento main deve ser único e não deve ser repetido em outras partes do documento.

### Código de Exemplo
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>

Identifique a seção main desta página para adicionar uma tag de abertura <main> antes do elemento h1, e uma tag de fechamento </main> depois do elemento p.

## Passo 6
No passo anterior, você colocou o h1, h2, comentário, e elementos p dentro do elemento main. Isto é conhecido como aninhamento. Elementos aninhados devem ser colocados dois espaços mais a direita do elemento que está aninhado. Este espaçamento é chamado identação e é usado para tornar a leitura do HTML mais fácil.

Aqui está um exemplo do aninhamento e identação:

### Código de Exemplo
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>

O elemento h1, elemento h2 e o comentário são identados dois espaços mais do que o elemento main no código abaixo. Use a barra de espaço no seu teclado para adicionar mais espaços na frente do elemento p assim que isto estiver identado corretamente também.

## Passo 7
Você pode adicionar imagens para o seu site usando o elemento img. Elemento img tem uma tage de abertura sem uma tag de fechamento. Um elemento sem uma tag de fechamento é conhecido como um elemento vazio.

Adicione um elemento img abaixo do elemento p. Neste ponto, a imagem não será exibida no navegador.

## Passo 8
Atributos HTML são palavras especiais usados dentro de uma tag de abertura de um elemento para controlar o comportamento dos elementos. O atributo src em um elemento img especifica a URL (local onde está localizado a imagem).

Aqui está um exemplo de um elemento img com o atributo src apontando para a logo do freeCodeCamp:

### Código de Exemplo
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">

Dentro do elemento img existente, adicione um atributo src com esta URL:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg

## Passo 9
Todo elemento img deve ter um atributo alt. O texto do atributo alt é usado para leitores de tela para melhorar a acessibilidade e é exibido se a imagem não for carregada.

Aqui está um exemplo de um elemento img com um atributo alt:

### Código de Exemplo
<img src="cat.jpg" alt="A cat">

Dentro do elemento img, adicione um atributo alt com este texto:

A cute orange cat lying on its back

## Passo 10
Você pode lincar outras páginas com o elemento âncora (a).

Aqui está um exemplo de ligação para https://www.freecodecamp.org:

### Código de Exemplo
<a href="https://www.freecodecamp.org"></a>
Adicione um elemento âncora depois do parágrafo que ligue ao https://freecatphotoapp.com. Neste ponto, o link não será exibido na pré-visualização.

## Passo 11
Uma texto associado é obrigatório ser colocado entre as tags de abertura e fechamento de um elemento âncora (a).

Aqui está um exemplo de um link com o texto click here to go to freeCodeCamp.org:

### Código de Exemplo
<a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>

Adicione o texto âncora cat photos para o elemento âncora. Isto se tornará o texto link.

## Passo 12
Adicione as palavras See more antes do elemento âncora e in our gallery depois do elemento âncora.

## Passo 13
Adicione tags p para tornar See more <a href="https://freecatphotoapp.com">cat photos</a> in our gallery. em um parágrafo.

## Passo 14
Torne o texto existente cute cats em um elemento âncora que ligue ao: 

https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg

## Passo 15
Abra o link em uma nova aba, você pode usar o atributo target no elemento âncora (a).

O atributo target especifica onde abrir o documento vinculado. target="_blank" abre o documento vinculado em uma nova aba ou janela.

Aqui está a syntax básica para um elemento com o atributo target:

### Código de Exemplo
<a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>

Adicione um atributo target com o valor _blank no elemento âncora (a) na tag de abertura, para que o link abra em uma nova aba.

## Passo 16
Agoa que você tem o link adicionado, você pode remover o comentário.

## Passo 17
No passo anterior, você usou um elemento âncora para tornar o texto em um link. Outros tipos de conteúdo também podem ser transformado em um link envolvidos por tags âncoras.

Aqui está um exemplo de transformação de imagem em um link:

### Código Exemplo
<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>
Torne a imagem em um link ao cercar ela com tags de elementos necessários. Use https://freecatphotoapp.com como o valor do atributo href da âncora.

## Passo 18
Antes de adicionar qualquer conteúdo novo, você deverá fazer uso de um elemento section para separar o conteúdo cat photos do conteúdo futuro.

O elemento section é usado para definir seções em um documento, tais como capítulos, cabeçalhos, rodapés, ou qualquer outra seção do documento. Este é um elemento semântico que ajuda com o SEO e acessibilidade.

### Código de Exemplo
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>

Torne seu elemento h2, os dois elemento p, o elemento âncora (a) e aninha-los em um elemento section.

## Passo 19
Está na hora de adicionar uma nova seção. Adicione um segundo elemento section abaixo do elemento section existente.

## Passo 20
Dentro do segundo elemento section, adicione um novo elemento h2 com o texto Cat Lists.

## Passo 21
Quando você adicona um cabeçalho de nível inferior para a página, está implícito que você está começando uma nova subseção.

Depois do último elemento h2 do segundo elemento section, adicione um elemento h3 com este texto:

Things cats love:

## Passo 22
Para criar uma lista de itens não ordenada , você pode usar o elemento ul.

Depois do elemento h3 com texto Cats love:, adicione um elemento de lista não ordenada (ul). Note que nada será exibido neste ponto.

## Passo 23
O elemento li é usado para criar um item de lista em uma lista ordenada e não ordenada.

Aqui está um exemplo de itens de lista em uma lista não ordenada:

### Código de Exemplo
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
Dentro do elemento ul aninhe três itens de lista para exibir três coisas que gatos amam:

catnip

laser pointers

lasagna

## Passo 24
Depois da lista desordenada, adicione uma nova imagem com o atributo src com o valor definido com:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg

E seu valor de atributo alt para:

A slice of lasagna on a plate.

## Passo 25
O elemento figure representa um conteúdo independente e permitirá você associar uma imagem com um caption.

Aninhe a imagem que você adicionou dentro de um elemento figure.

## Passo 26
Um elemento de legenda da figura (figcaption) é usado para adicionar uma legenda para descrever a imagem contida no elemento da figura.

Aqui está um exemplo de um elemento figcaption com a legenda de A cute cat:

## Código de Exemplo
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
Despois de aninhar a imagem no elemento figure, adicione um elemento figcaption com o seguinte texto:

Cats love lasagna.

## Passo 27
Para colocar ênfases em uma palavra específica ou frase, você pode usar o elemento em.

Enfatize a palavra love no elemento figcaption, envolvendo-o em um elemento de ênfase.

## Passo 28
Após o elemento figure, adicione outro elemento h3 com o texto:

Top 3 things cats hate:

## Passo 29
A programação para uma lista ordenada (ol) é similar a uma lista não ordenada , mas itens de lista em uma lista ordenada são numerada assim que exibido.

Abaixo do elemento h3, adicione uma lista ordenada com estes três itens da lista:

flea treatment thunder other cats

## Passo 30
Após a lista ordenada, adicione outro elemeto figure.

## Passo 31
Dentro do elemento figure que você acabou de adicionar, aninhe um elemento img com um atributo src definido como https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg.

## Passo 32
Para melhorar a acessibilidade da imagem que você adicionou, adicione um atributo atl como texto:

Five cats looking around a field.

## Passo 33
Após ao último elemento img, adicione um elemento figcaption com o texto Cats hate other cats.

## Passo 34
O elemento strong é usado para indicar que alguns textos é de forte importancia ou urgente.

No figcaption que você acabou de adicionar, indicar que hate é de extrema importância envolvendo-o em um elemento strong.

## Passo 35
O elemento footer é usado para definir um rodapé para um documento ou seção. Normalmente um rodapé contém informações sobre o autor do documento, dados de copyright, links para termos de uso, informações para contato e muito mais.

Após o elemento main, adicione um elemento footer.

## Passo 36
Aninhe um elemento p com o texto No Copyright - freeCodeCamp.org dentro do elemento footer.

## Passo 37
Transforme o texto existente freeCodeCamp.org em um link colocando ele em um elemento âncora (a). O atributo href deverá ser definido para  https://www.freecodecamp.org

## Passo 38
Observe que tudo o que você adicionou à página até agora está dentro do elemento body. Todos os elementos de conteúdo da página que devem ser renderizados para a página vão dentro do elemento body. No entanto, outras informações importantes vão para dentro do elemento principal.

O elemento head é usado para conter metadados sobre o documento, como seu título, links para folhas de estilo e scripts. Metadados são informações sobre a página que não são exibidas diretamente na página.

Adicione um elemento de cabeça acima do elemento de corpo.

## Passo 39
O elemento title determina o que será exibido no navegador na barra de título ou na aba para página.

Adicione um elemento title dentro do elemento head uando o texto abaixo:

CatPhotoApp

## Passo 40
Note que o conteúdo inteiro da página está aninhado dentro de um elemento html. O elemento html é o elemento raiz de uma página HTML e todo seu conteúdo envolvido na pátgina.

Você também pode especificar a linguagem da sua página adicionando o atributo lang no elemenot html.

Adicione o atributo lang com o valor na tag de abertura html para especificar que a linguagem da página está em Inglês.

Passo 41
Todas as páginas devem começar com <!DOCTYPE html>. Esta string especial é conhecida como uma declaração e garante que o navegador tenta atender às especificações de toda a indústria.

<!DOCTYPE html> diz aos navegadores que o documento é um documento HTML5, que é a versão mais recente do HTML.

Adicione esta declaração como a primeira linha do código.

Passo 42
Você pode definir o comportamento do navegador adicionando elementos meta na cabeça. Aqui está um exemplo:

### Código de exemplo
<meta attribute="value">
Dentro do elemento head, aninhe um meta elemento com um atributo charset definido para o valor de utf-8. Isso diz ao navegador como codificar caracteres para a página.

Note que o meta elemento é um elemento vazio.

Com essa última mudança, você completou o workshop do Cat Photo App. Parabéns!