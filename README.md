Simulador de Ganhos
Este é um simulador de ganhos baseado em um sistema de comissões, onde o usuário pode calcular os ganhos de acordo com a quantidade de diferentes categorias (Diamante, Ouro e Prata) para diferentes gerações. O simulador permite que o usuário calcule os valores ganhos e o que deixou de ganhar de acordo com o pacote escolhido.

Funcionalidades
Escolha de Pacote: O usuário pode selecionar entre três pacotes de comissões:

Diamante (até 10ª geração)
Ouro (até 7ª geração)
Prata (até 4ª geração)
Tabelas de Geração: A tabela exibe as gerações, permitindo ao usuário inserir a quantidade de itens para cada categoria (Diamante, Ouro, Prata) para cada geração. A cada linha da tabela, o sistema calcula e exibe o valor correspondente aos ganhos com base na comissão da respectiva geração.

Comissões: As comissões para cada geração são definidas no sistema e variam entre 1% e 20%.

Cálculo de Ganhos: Ao pressionar o botão "Calcular", o sistema soma os valores dos itens informados, multiplicados pela comissão da geração, e exibe o total de ganhos e o que deixou de ganhar (caso o usuário tenha escolhido um pacote que não cobre todas as gerações).

Resetar Valores: O botão "Apagar" limpa todos os campos e reinicia o simulador para um novo cálculo.

Estrutura do Projeto
HTML
A estrutura principal da página é feita em HTML. A tabela de entradas é gerada dinamicamente através de JavaScript.
A página também contém botões interativos para calcular os ganhos e limpar os campos.
CSS
O design da página é feito com CSS, que garante que a interface seja responsiva e fácil de usar.
A tabela é estilizada para destacar as células e tornar a visualização dos resultados mais clara.
A página é adaptada para diferentes tamanhos de tela usando consultas de mídia (media queries), garantindo que o layout seja adequado para dispositivos móveis e desktops.
JavaScript
Função createTableRows: Esta função cria as linhas da tabela dinamicamente, permitindo que o número de gerações seja configurado de forma flexível. Cada linha tem campos para entrada de valores e exibe os resultados calculados.

Função calculate: Realiza o cálculo dos ganhos com base nos valores inseridos nas entradas e nos pacotes selecionados.

Função reset: Limpa todos os campos de entrada e resultados.

Como Usar
Selecione o Pacote: Escolha um pacote de comissão (Diamante, Ouro ou Prata) a partir do menu suspenso.
Preencha os Valores: Insira a quantidade de itens nas colunas correspondentes a cada geração para cada categoria (Diamante, Ouro e Prata).
Calcule os Ganhos: Clique no botão "Calcular" para ver o total de ganhos e o que deixou de ganhar.
Apague os Valores: Se desejar reiniciar o simulador, clique no botão "Apagar" para limpar os campos.
Exemplos de Uso
Se você escolheu o pacote Diamante, poderá preencher as quantidades para até a 10ª geração. Cada geração terá um percentual de comissão correspondente (20% para a 1ª geração, 5% para a 2ª, 1% para as seguintes).

Se você preencher a quantidade de itens e clicar em "Calcular", o sistema irá multiplicar a quantidade de itens pela comissão da geração correspondente e somar os resultados.

Tecnologias Utilizadas
HTML: Para estruturação da página.
CSS: Para design e responsividade da página.
JavaScript: Para a lógica do simulador e interatividade.
Personalização
As taxas de comissão podem ser facilmente ajustadas no código JavaScript, caso seja necessário atualizar as porcentagens para cada geração.
O número máximo de gerações pode ser alterado no código de acordo com os requisitos do sistema.
Contribuindo
Se desejar contribuir para o projeto, siga os passos abaixo:

Faça um fork deste repositório.
Crie uma branch para suas alterações (git checkout -b nova-feature).
Faça suas alterações e commit (git commit -am 'Adiciona nova feature').
Envie para o repositório remoto (git push origin nova-feature).
Abra um pull request para o repositório principal.
Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
