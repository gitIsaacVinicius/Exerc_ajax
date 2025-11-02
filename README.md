# Atividade sobre AJAX - Linguagem de Programação para a Web I
#### Aluno: Isaac Vinícius
### 1. Elabore uma pesquisa comparando XmlHttpRequest, fetch, Promises e async/await
---
**XmlHttpRequest** (XHR) é a API original do navegador para fazer requisições HTTP. Funciona baseada em eventos e callbacks, que são funções passadas como argumento para serem chamadas quando algo acontece. Fornece uma maneira fácil de recuperar dados de um URL sem a necessidade de atualizar a página inteira. Isso permite que uma página da Web atualize apenas uma parte do conteúdo sem interromper o que o usuário esteja fazendo.

**Fetch** é uma API moderna do navegador para fazer requisições HTTP e que substitui o XHR. Fornece uma função global (fetch()) que retorna uma Promise, maneira fácil e lógica para buscar recursos de forma assíncrona através da rede. Por usar Promises, o código é mais limpo.

As **Promises** não são uma ferramenta de requisição, mas sim um novo padrão para lidar com código assíncrono. É um objeto que representa a eventual conclusão (ou falha) de uma operação assíncrona. Tem três estados: pending (pendente), fulfilled (realizada com sucesso) ou rejected (rejeitada com erro). A Promise é o conceito central que permite o fetch e o async/await existirem.

O **async/await** é uma sintaxe especial que permite escrever código assíncrono que parece síncrono. O async é usado para declarar que uma função vai lidar com operações assíncronas. Já o await é utilizado dentro de uma função async, ele "pausa" a execução da função (sem travar o navegador) e espera a Promise ser resolvida. É a mais limpa e legível de todas as descritas.