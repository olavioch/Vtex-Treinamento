criando um codigo css para o vtex:
    * primeiro: inspecione a pagina "link/?__inspect"
    * segundo: crie um arquivo css de acordo com o componente inspecionado vtex.appinspecionado.css
    * terceiro: aplique o estilo com blockClass para um elemento especifico e sem blockClass para o componente geral
    * quarto: Na falta de um css handle na documentação, usar o css global do vtex.
        exemplo: ":global(vtex-componentName)"