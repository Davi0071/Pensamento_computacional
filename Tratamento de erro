"Entrega Projeto Aula – Pensamento Computacional para Sistemas de Larga Escala"

Alunos/Integrantes 
Davi Lima Nunes de Oliveira — RGM: 44309147 
Vitor Pereira da Silva Martins — RGM: 43952810 

1. Problema na Decomposição

As etapas estão muito genéricas e algumas não são indispensáveis para a compra do ingresso.

Uma forma melhor de ser descrever a ação seria:

Acessar a plataforma de venda.
Fazer login ou cadastro.
Selecionar o evento.
Escolher quantidade e tipo de ingresso.
Confirmar os dados da compra.
Selecionar a forma de pagamento.
Realizar o pagamento.
Receber a confirmação.
Acessar o ingresso digital.

2. Problema na Lógica do Fluxo

Existe uma etapa importante ausente:
Após escolher o evento, normalmente o usuário precisa:

Escolher setor/assento (quando disponível).
Definir quantidade de ingressos.

Sem essas etapas, o algoritmo fica incompleto.

3. Problema na Sequência de Pagamento

A etapa:

"Geração do código de pagamento"

não ocorre em todos os casos.

Por exemplo:

Cartão de crédito → não gera código.
PIX → gera QR Code ou chave.
Carteira digital → pagamento direto.

Logo, a abstração utilizada pode induzir a erro.

Melhor descrição:

"Escolha da forma de pagamento e geração das informações para pagamento."

4. Falha na Abstração

O texto afirma:

"O projeto considera apenas as ações essenciais necessárias para concluir a compra do ingresso"

Porém foram incluídas ações não essenciais:

Acesso ao celular.
Desbloqueio do aparelho.

Isso contradiz o próprio conceito de abstração, que consiste em eliminar detalhes irrelevantes.

5. Reconhecimento de Padrões Pouco Desenvolvido

A seção cita:

Plataformas de comércio eletrônico.
Sistemas digitais de pagamento.
Aplicativos de autenticação.

Mas não explica quais padrões foram identificados.

Seria melhor mencionar exemplos como:

Login e autenticação de usuários.
Carrinho de compras.
Seleção de produtos/eventos.
Processamento de pagamentos.
Emissão de comprovantes digitais.

6. Algoritmo Incompleto

O algoritmo não prevê situações alternativas, por exemplo:

Pagamento recusado.
Falha na internet.
Evento esgotado.
Dados preenchidos incorretamente.

Um algoritmo computacional normalmente considera condições e decisões.

ATIVIDADE CORRIGIDA

Pensamento Computacional Aplicado
1. Decomposição

A decomposição consiste em dividir um problema complexo em partes menores e mais simples de serem compreendidas e executadas.

O processo de compra de ingressos foi dividido nas seguintes etapas:

Acessar a plataforma de venda de ingressos.
Realizar login ou cadastro na plataforma.
Pesquisar e selecionar o evento desejado.
Escolher a quantidade de ingressos.
Selecionar setor ou assento (quando disponível).
Confirmar os dados da compra.
Escolher a forma de pagamento.
Realizar o pagamento.
Receber a confirmação da compra.
Visualizar ou baixar o ingresso digital.

2. Reconhecimento de Padrões

O reconhecimento de padrões permite identificar características e procedimentos que se repetem em diferentes sistemas.

Autenticação de usuários por login e senha.
Pesquisa e seleção de produtos ou serviços.
Preenchimento e validação de dados.
Escolha de métodos de pagamento.
Confirmação automática da transação.
Emissão de comprovantes e documentos digitais.

Esses padrões são comuns em plataformas de comércio eletrônico, aplicativos de serviços e sistemas digitais de pagamento.

3. Abstração

A abstração consiste em focar apenas nas informações relevantes para resolver o problema, ignorando detalhes desnecessários.

Neste projeto foram consideradas apenas as etapas essenciais para a compra do ingresso, desconsiderando elementos como:

Desbloqueio do celular.
Abertura do navegador.
Configurações do dispositivo.
Notificações do sistema.

O foco permanece exclusivamente nas ações necessárias para concluir a aquisição do ingresso.

4. Algoritmo

A sequência lógica das ações pode ser representada pelo seguinte algoritmo:
INÍCIO

Acessar a plataforma de ingressos

SE usuário não possuir cadastro
    Realizar cadastro
SENÃO
    Fazer login
FIMSE

Pesquisar evento desejado

SE houver ingressos disponíveis
    Selecionar quantidade de ingressos
    Escolher assento ou setor (quando disponível)
    Confirmar compra
    Selecionar forma de pagamento
    Efetuar pagamento

    SE pagamento aprovado
        Exibir confirmação da compra
        Disponibilizar ingresso digital
    SENÃO
        Informar falha no pagamento
    FIMSE

SENÃO
    Informar indisponibilidade de ingressos
FIMSE

FIM

CONCLUSÃO

A aplicação do pensamento computacional permitiu transformar o processo de compra de ingressos online
em uma sequência organizada de etapas, facilitando sua análise e representação.
Por meio da decomposição, abstração, reconhecimento de padrões e elaboração de algoritmos, foi possível 
compreender melhor o funcionamento do sistema e identificar como problemas do cotidiano podem ser modelados
de maneira lógica e estruturada. Essa abordagem demonstra a importância do pensamento computacional
na resolução de problemas e no desenvolvimento de soluções tecnológicas eficientes.
