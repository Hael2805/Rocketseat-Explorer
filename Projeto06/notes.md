# DOM:
 
 * Document Object Model 
  - Modelagem do documento como objetivo JavaScript

 * Representação do HTML em objetos JavaScript 
  - Atributos (propriedades) e métodos (funcionalidades) 

 * Criado pelo navegador (browser) 
  - É uma interface (API) usada no navegador  

- -  JS -> DOM <- HTML - 

# Pra que serve:

 * JavaScript usa a DOM para se conectar ao HTML
  - DOM nao é o JavaScript 

 * Manipular o HTML com JavaScript 
  - Modificar o HTML, os estilos e até disparar ações  

# Dev tools 
 * Através das ferramentas do desenvolvedor >Dev Tools< observamos a DOM.

 * Objeto global presente em qualquer página no navegador 
  - window 

 * Representação do documento 
  - document  

# Element e Node 
 * As tags HTML, quando usadas pela DOM, podemos chamar de node (nó) ou de element (elemento)

 * pegando um elemento 
  - const h1 = document.querySelector('h1') // HTMLElement 

 * Pegando vários elementos 
  - const links = document.querySelectorAll('a') // Nodelist 

# Recebendo e modificando valores 
 * Podemos pegar qualquer valor das tags e também alterar eles 

 * innerText 
  - console.log(h1.innerText) 

 * innerHTML 
  - console.log(h1.innerHTML) 

 * alterando o texto (ou HTML) 
  - h1.innerText = "Novo título" 

# Podemos alterar estilos ou adicionar classes em elementos 

 * alterando o estilo 
  - h1.style.backgroundColor ="red" 

 * adicionando classes 
  - h1.classList.add('hide') 

 * removendo classes
  - h1.classList.remove('hide') 

 * alternando entre classes 
  - h1.classList.toggle('hide') 

-------------

# Event-driven 

 * A DOM é direcionada a eventos Event-driven, significa que ela poderá reagir a qualquer tipo de evento relacionado à página.

 * Podemos entender em duas fases 
  - A ocorrência do eveno e reação à ocorrência 

# 1. Eventos 
 * Ações que acontece na página, site ou aplicação 
  - Carregamento do documento, aparição de elementos na tela 
  - Modificação de propriedades da página (largura, altura, scroll) 
  - Cliques de mouse e digitação do teclado 
  - Interação com sons, imagens e vídeos 
  - Outros 

# 2. Reações 
 * O sistema poderá executar reações às ações, executar uma função sempre que determinada ação acontecer
