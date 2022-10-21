![ProjetoToDoList](https://user-images.githubusercontent.com/100232025/197286061-32e334c5-5d7a-4335-9068-c04cf85e627a.gif)
# TO DO LIST
Este foi um projeto desenvolvido no segundo período da minha faculdade, colocando em prática partes do meu aprendizado na disciplina de Programação Web.

Link da hospedagem do site: https://projetos-front-end.vercel.app

## Estrutura do Site

O site funciona como uma grande lista de afazres, no qual, por meio de uma interface simples e minimalista o usuário consegue executar as seguintes atividades:
- Adicionar Atividades: Apenas preenchendo o input (caixa de entrada) e pressionando o botão com símbolo de push;
- Excluir Atividades: Apenas clicando no botão de "remover";
- Check: Ato de validar uma atividade feita;
 
## Conteúdo
- JavaScript
  - Lógica de Programação 
  - Vanilla JS
 - Ferramentas Externas
   - Boosttrap - Framework usado para dar um suporte na estilziação CSS.
   - Back4App - Usado para armazenar todos os dados recolhidos no site e sistematizar os checkout.
  
## Implementação das Ferramentas e Tecnologias

Para a desenvoltura do site foi feito um HTMl básico, contendo título, input, botão de adicionar e remover, além de algumas div, sendo a maioria usada pelo CSS, enquanto 
que outra focada em, através do JS, alocar todos os dados. 

No JavaScript foram estipuladas funções de:
- gerarLista(): Usando recursos como inner.html/createTextNode/AppendChild/Onclick/Checked, além de 
estruturas de repetição como For para, como o nome da função diz, gerar a criação de uma lista.
- exibirTarefa(): Essa função é mais um display, funcionando para através da div que vai
englobar os dados, a qual fizemos no html mostrar todas as atividades, juntamente com o botão "remover". Isso pré-estabelecido na função anterior.
- criarTarefa();
- atualizarTarefa(): Essa função serve para puxar os dados e quando o usário clicando no checkbox, a funçaõ se encarregará de emitir um alerta para o Back4App atualizando o valor como "True";
- removerTarefa();

Tudo isso foi possível com os códigos base feitos pela ferramenta Back4App.
