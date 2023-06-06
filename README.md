# Promises
- Uma promise é uma forma mais fácil de trabalhar com códigos assíncronos no javascript. Ela é um objeto que é instanciado através da classe Promise e recebe uma função como parâmetro. Essa função é executada quando a promise é criada, porém sem bloquear a execução do código:
- Uma promise possui diferentes estados, que são: pendente (estado padrão), rejeitada e resolvida (ou cumprida). A promise ficará em estado pendente até que seja resolvida utilizando o primeiro parâmetro da função usada na sua construção. Esse primeiro parâmetro é uma função que “resolve” a promise e passa adiante o valor do resultado
- Por fim, a prática comum ao usar as promises é retorná-las no final de uma função, assim elas serão executadas quando a função for chamada:

# Também podemos rejeitar a promise caso queiramos indicar que algo deu errado:
- Obs.: repare que nesse caso a rejeição da promise é como um erro no código, que se não for tratado adequadamente irá resultar no término da aplicação. Veremos como fazer isso na próxima aula.
