
# Página exemplo: Instruções básico Bootstrap
--------

### *Basecamp: Philips FullStack Developer.*
Esta atividade faz parte de um módulo desenvolvido no bootcamp: Philips Fullstack Developer │ You are You.



### Atividade
* Criar uma página de exemplo utilizando bootstrap.

#### Dicas
#### **sobre hierarquias de seletores**

Em CSS existem, basicamente, três tipos de seletores comuns: por tagHTML, porID e porClasse. Estes seletores apresentam hierarquia entre sí (porID>porClasse>PortagHTML) e conhece-las pode evitar possíveis confusões durante o processo de construção de páginas httml com css e durante possíveis usos de códigos provenientes do projeto bootstrap. 
Para referencia-los no código css utiliza-se, respectivamente: tag_html, #classe_html, #id_html :

*Exemplo de seletores :*
```sh
h1{
    background-color: aquamarine;
    text-align: center;
    color: blueviolet;
}
.seletorPorClasse{
    background-color: rgb(235, 188, 59);
    text-align: center;
    color: rgb(72, 16, 124);
}
#seletorPorID{
    background-color: rgb(235, 59, 220);
    text-align: center;
    color: rgb(251, 247, 255);
}
```
No exemplo abaixo, para evidenciar a hierarquia entre os seletores, um texto é estilizado por três seletores diferentes sendo que, ao inserir os seletores todos sobre mesmo texto (hello world) apenas um estilo é aplicado, seguindo, obviamente, a hierarquia definida entre os seletores (porID>porClasse>PortagHTML).
*Exemplo prático da hierarquia dos seletores :*
![gifHierarquiaSeletores](https://user-images.githubusercontent.com/64921117/159170791-03355a63-4215-4fe5-90d8-da3324fb90f4.gif)



