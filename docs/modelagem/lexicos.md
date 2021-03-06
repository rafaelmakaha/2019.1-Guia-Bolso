## Introdução

Trata-se de uma técnica que procura descrever os símbolos de uma linguagem. O principal objetivo a ser perseguido pelos Engenheiros de Requisitos é a identificação de palavras ou frases peculiares ao meio social e da aplicação sob estudo.


## Metodologia

Para a confecção dos léxicos o grupo utilizou cards com o seguinte modelo base:

| **LXX** | **Nome do léxico**  |
|--|--|
| **Versão**| Atual: 1.1 (Data) <br> Anterior: [1.0](#) |
| **Autor**| Autor(es) do léxico |
| **Classificação** | Classificação do léxico (estado, objeto ou verbo) |
| **Sinônimos** | Sinônimos do léxico |
| **Noção** | Noções do léxico | 
| **Impacto** | Impactos do léxico |
| **Rastro** | Rastro do léxico |

Para o levantamento inicial de palavras e termos, o grupo realizou um [Brainstorm](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso). A partir daí, e dos próprios léxicos foram aparecendo outros termos que o grupo julgou interessante serem modelados.

## Léxicos

### L1 - Nome Sujo

| **L1** | **Nome Sujo**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l1-nome-sujo_1) |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Estado |
| **Sinônimos** | Devedor, caloteiro |
| **Noção** | > Quando uma pessoa possui nome sujo no serasa <br> > O nome da pessoa está no cadastro da dívida ativa de órgãos de cobrança <br> > Status da pessoa que não honra com suas dívidas | 
| **Impacto** | > O [usuário](#l13-usuario) com o nome sujo não faz empréstimos <br> > O [usuário](#l13-usuario) com o nome sujo não consegue contratar alguns serviços <br> > Operadoras de cobrança ligam constantemente para o [usuário](#l13-usuario) com o nome sujo |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L2 - Cadastro positivo

| **L2** | **Cadastro Positivo**  |
|--|--|
| **Versão**| Atual: 1.1 (17/04/19) <br> Anterior: [1.0](#l2-cadastro-positivo_1) | 
| **Autor**| [Shayane Alcântara](https://github.com/shayanealcantara) |
|**Classificação**| Objeto |
|**Sinônimos**| <br> > [Empresas](#l31-instituicoes-financeiras) verem o usuário de forma positiva; <br> > Boa reputação no mercado.|
| **Noção** | > Quando uma pessoa não possui dívidas; <br> > Pessoa no cadastro de "Bom pagador"; <br> > Pessoa que quer bem visto pelas [instituições](#l31-instituicoes-financeiras); <br> > Quando uma pessoa quer ser vista não só pelas dívidas no seu nome, mas pelo seus hábitos financeiros; <br> Quando uma pessoa quer que seu nome seja visto positivamente ao ser consultado por [empresas](#l31-instituicoes-financeiras). |  
| **Impacto** | > O [usuário](#l13-usuario) que está no cadastro positivo tem maior facilidade de fazer empréstimos <br> > O indivíduo que está no cadastro positivo tem uma maior linha de crédito (#l6-credito-pre-aprovado) <br> > O indivíduo que está no cadastro positivo consegue juros menores em certas [operações bancárias](#l42-transacao). |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L3 - Consultar CPF

| **L3** | **Consultar CPF**  |
|--|--|
| **Versão**| Atual: 1.0 (27/04/19) <br> Anterior: - | 
| **Autor**| [Shayane Alcântara](https://github.com/shayanealcantara) |
|**Classificação**| Objeto |
|**Sinônimos**|<br> > Verificar CPF; <br> > Verificar se o nome está [sujo](#l1-nome-sujo) ou [limpo(#l24-nome-limpo).|
| **Noção** | > Verificar, por intermédio do Guiabolso, o status de devedor (ou não) de um [indivíduo](#l39-individuo) no Boa Vista SCPC; <br> > Verificar se o [usuário](#l13-usuario) está com o [nome sujo](#l1-nome-sujo) ou o [nome limpo](#l24-nome-limpo). |
| **Impacto** | > Ao consultar o cpf, um [indivíduo](#l39-indiiduo) com o [nome sujo](#l1-nome-sujo) pode saber quais são suas dívidas; <br> > Ao consultar o cpf, um [indivíduo](#l39-individuo)] pode saber se está no [cadastro positivo](#l2-cadastro-positivo); <br> > Ao consultar o cpf, um indivíduo](#l39-individuo) passar a saber seu [score do Serasa](#l4-score-do-serasa).|
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L4 - Score do Serasa

| **L4** | **Score do Serasa**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l4-score-do-serasa_1) |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Objeto |
| **Sinônimos** | Pontuação |
| **Noção** | > Pontuação numérica que classifica economicamente uma pessoa <br> > Chance percentual de um indivíduo não pagar uma conta | 
| **Impacto** | > Um indivíduo com o score do serasa alto tem o [cadastro positivo](#l2-cadastro-positivo) aceito <br> > Um indivíduo com o score do serasa baixo tem uma chance alta de estar com o [nome sujo](#l1-nome-sujo) <br> > Um indivíduo com o score do serasa baixo tem dificuldade em conseguir um [crédito pré-aprovado](#l6-credito-pre-aprovado) |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L5 - Dívida ativa

| **L5** | **Dívida Ativa**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l5-divida-ativa_1) |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Objeto |
| **Sinônimos** | Negativado, cadastro devedor |
| **Noção** | > Inserção do nome de um indivíduo com o status de [nome sujo](#l1-nome-sujo) no cadastro de devedores dos serviços de proteção de crédito <br> > Estar com o [nome sujo](#l1-nome-sujo) | 
| **Impacto** | > Um [usuário](#l13-usuario) que está na dívida ativa tem seu [score do serasa](#l4-score-do-serasa) reduzido <br> > Um [usuário](/#l13-usuario) que está na dívida ativa tem uma redução de linhas de crédito |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |


### L6 - Crédito Pré-aprovado

| **L6** | **Crédito Pré-aprovado**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l6-credito-pre-aprovado_1) |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Objeto |
| **Sinônimos** | Crediário, cheque-especial, limite |
| **Noção** | > Valor em dinheiro disponibilizado por instituições financeiras para um indivíduo resgatar a qualquer momento <br> > Dinheiro disponibilizado através de uma análise prévia feita por bancos e instituições financeiras | 
| **Impacto** | > Ao resgatar o crédito pré-aprovado, um indivíduo estará fazendo uma dívida <br> > Ter um crédito pré-aprovado alto significa ter uma boa análise de crédito e [score do serasa](#l4-score-do-serasa) |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L7 - Comprometimento de renda

| **L7** | **Comprometimento de renda**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l7-comprometimento-de-renda_1) |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Estado |
| **Sinônimos** | Salário líquido, impedimento |
| **Noção** | > Quando um indivíduo tem parte do seu dinheiro já destinado à algum gasto <br> > Indivíduo com uma dívida que reduz seu salário bruto | 
| **Impacto** | > Um indivíduo com a renda comprometida tem dificuldades em gerenciar seu dinheiro <br> > Um indivíduo com a renda comprometida não possui um bom [crédito pré-aprovado](#l6-credito-pre-aprovado) <br> > Um indivíduo com a renda comprometida pode não conseguir um empréstimo |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |


### L8 - Simulação

| **L8** | **Simulação**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l8-simulacao_1) |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Verbo |
| **Sinônimos** | Fingir |
| **Noção** | > Fazer um empréstimo fantasioso <br> > Fingir fazer um empréstimo para saber as condições e consequências |
| **Impacto** | > Um indivíduo faz uma simulação, conhecendo valores e prazos de um empréstimo <br> > Após fazer a simulação  indivíduo pode optar por contratar ou não o seu [crédito pré-aprovado](#l6-credito-pre-aprovado) <br> > Fazendo um empréstimo após uma simulação, um indivíduo passar a ter parte da sua [renda comprometida](#l7-comprometimento-de-renda) |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |


### L9 - Contas residenciais

| **L9** | **Contas residenciais**  |
|--|--|
| **Versão**| Atual: 1.0 (27/04/19) <br> Anterior: - |
| **Autor**| [Shayane Alcântara](https://github.com/shayanealcantara) |
|**Classificação**| Objeto |
|**Sinônimos**|<br> > Contas de casa; <br> Gasto de água, luz e internet.|
| **Noção** | > Categoria pertencente ao grupo de gastos essenciais do [usuário](/#l13-usuario) do Guiabolso <br> > Categoria para registros de gastos com fins residenciais, como despesas de água, luz <br> > Tipo de categoria para o [usuário](/#l13-usuario) que deseja categorizar seus gastos para incluí-los no [planejamento](#l40-planejamento-financeiro) dos [meses futuros](#l18-meses-futuros); | 
| **Impacto** | > [Usuário](/#l13-usuario) registra uma conta residencial e a categoriza, de modo que ele possa visualizar seus gráficos de gastos de forma mais organizada e assim, facilitar seu [planejamento](#l40-planejamento-financeiro); <br> > A categoria de Contas Residenciais consta no [planejamento](#l40-planejamento-financeiro) de [renda](/#l28-renda); <br> > Gastos com estabelecimento que tenham nomes intuitivos podem ser relacionados à categoria de Contas Residenciais automaticamente, por exemplo: Companhia Energética de Brasília (CEB). |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L10 - Pausar cartão

| **L10** | **Pausar cartão**  |
|--|--|
| **Versão**| Atual: 1.1 (17/06/19) <br> Anterior: [1.0](#l10-pausar-cartao_1) |
| **Autor**| [Rafael Makaha](https://github.com/rafaelmakaha) |
|**Classificação**| Verbo |
|**Sinônimos**| > Interromper informações do cartão <br> > Sessar dados |
| **Noção** | > Impedir que o aplicativo atualize os dados (gastos e/ou pagamentos) de determinado cartão <br> > Fazer com que um cartão não seja atualizado dentro do Guiabolso, temporariamente |
| **Impacto** | > Ao pausar um cartão, o [usuário](/#l13-usuario) não terá mais uma gerência de gastos dele |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L11 - Conta manual

| **L11** | **Conta manual**  |
|--|--|
| **Versão**| Atual: 1.0 (27/04/19) <br> Anterior: - |
| **Autor**| [Shayane Alcântara](https://github.com/shayanealcantara) |
|**Classificação**| Objeto |
|**Sinônimos**| <br> > Conta em que o próprio [usuário](/#l13-usuario) adiciona gastos; <br> > Semelhante ao costume de adicionar gastos, [rendas](#l38-renda) e [metas](#l23-meta) no bloco de notas ou [agenda](#l36-agenda); <br> > Contrária à [Conta Automática](#l12-conta-automatica). |
| **Noção** | > Opção de escolha com o intuito de como a conta do [usuário](/#l13-usuario) será registrada; <br> > Tipo de conta em que o [usuário](/#l13-usuario) não insere seus [dados bancários](#l39-dados-bancarios) no aplicativo; <br> > Tipo de conta em que o [usuário](/#l13-usuario) deseja adicionar [transações](#l42-transacao) manualmente; <br> > Alternativa à [Conta Automática](#l12-conta-automatica). |
| **Impacto** | > A conta manual não sofre sincronização automática; <br> > O [usuário](/#l13-usuario) adiciona manualmente as [transações](#l42-transacao) de sua escolha. |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L12 - Conta automática

| **L12** | **Conta automática**  |
|--|--|
| **Versão**| Atual: 1.0 (27/04/19) <br> Anterior: - |
| **Autor**| [Shayane Alcântara](https://github.com/shayanealcantara) |
| **Classificação**| Objeto |
|**Sinônimos**| <br> > Semelhante ao [extrato](#l21-extrato) ou fatura do [banco](#l31-instituicoes-financeiros); <br> > [Usuário](#l13-usuario) não precisa inserir nada, é automático; <br> > Contrária à [Conta Manual](#l11-conta-manual).|
| **Noção** | > Meio de registrar [transações](#l42-transacao) de forma automática com a conta bancária; <br> > [usuário](#l13-usuario) insere seus dados bancários no aplicativo para importação de dados. |
| **Impacto** | > O extrato do [usuário](/#l13-usuario) é constantemente atualizado para seu acompanhamento ou [planejamento](#l40-planejamento-financeiro), tornando-o fiél; <br> > Permite um acompanhamento ou [planejamento](#l40-planejamento-financeiro) prático das [transações](#l42-transacao) financeiras. |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L13 - Usuário

| **L13** | **Usuário**  |
|--|--|
| **Versão**| 1.0 |
| **Autor**| [Lucas Machado](https://github.com/lmmLucasMachado) |
| **Classificação**| -- |
| **Sinônimos**| -- |
| **Noção** | > Indivíduo que utiliza o aplicativo Guiabolso |
| **Impacto** | > O usuário instala o Guiabolso <br> > O usuário tem maior controle financeiro <br> > O usuário tem acesso à simulação de empréstimos, pode consultar seu cpf dentre outros |
| **Rastro** | [Rich picture preocupações do usuário](../../pre-rastreabilidade/richpicture/#rp03-preocupacoes-do-usuario) |

### L14 - Transações ignoradas

| **L14** | **Transações ignoradas**  |
|--|--|
| **Versão**| Atual: 1.1(23/04) <br> Anterior: [1.0](../lexicos/#l14-transacoes-ignoradas_1) |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | Gastos ignorados |
| **Noção** | > Movimentações na conta que o [usuário](#l13-usuario) deseja ignorar. |
| **Impacto** | > Transações ignoradas não são rastreadas nos gastos; <br> > Com algumas transações sendo ignoradas, o [usuário](#l13-usuario) pode dar mais atenção a transações que considera mais importantes; <br> > O [usuário](#l13-usuario) pode se esquecer de que um determinado gasto está como transação ignorada e atrapalhar seu [planejamento financeiro](#l40-planejamento-financeiro). |
| **Rastro** | [Cenário 7](../cenarios/#c7-ignorar-transacao) |

### L15 - Crediário

| **L15** | **Crediário**  |
|--|--|
| **Versão**| Atual: 1.1(23/04) <br> Anterior: [1.0](../lexicos/#l15-crediario_1) |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | Carnê |
| **Noção** | > Forma de financiamento de bens e serviços; <br> > Parcelamento em carnê; | 
| **Impacto** | > As parcelas do crediário são fixas acrescidas de juros e correção monetária; <br> > Fazendo o crediário, o [indivíduo](#l39-individuo) sai do estabelecimento sabendo exatamente quanto pagará e a data de vencimento de cada parcela; <br> > O crediário permite parcelamento em até 48x, facilitando a perda de controle de boletos e o endividamento; <br> > Fazer um crediário é fazer [comprometimento de renda](#l7-comprometimento-de-renda) a longo prazo. |
| **Rastro** | Não possui |

### L16 - Internet Banking

| **L16** | **Internet Banking**  |
|--|--|
| **Versão**| Atual: 1.1(23/04) <br> Anterior: [1.0](#l16-internet-banking_1) |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | Site do Banco |
| **Noção** | > Ambiente bancário na Internet; <br> > Site com alto nível de segurança onde ficam disponíveis serviços oferecidos pelos [bancos](#l31-instituicao-financeira); <br> > Acesso ao serviços bancários pelo computador/navegador. |
| **Impacto** | > O Internet Banking evita o descolocamento até agência bancária ou [caixa eletrônico](#l34-caixa-eletronico) <br> > Por vezes, é necessária a instalação de plugins de segurança para que o Internet Banking seja usado. |
| **Rastro** | [Cenário 10](../cenarios/#c10-solicitar-credito-pre-aprovado) |

### L17 - Status

| **L17** | **Status**  |
|--|--|
| **Versão**| Atual: 1.1 (21/04) <br> Anterior: [1.0](#l17-status_1) |
| **Autor**| [Marcelo Araújo](https://github.com/santosm46) |
| **Classificação**| Objeto |
| **Sinônimos**| Conta atualizada |
| **Noção** | > Mostra a situação da conta do(s) cartão(ões) <br> > Informa se as informações sobre transações do cartão estão atualizadas|
| **Impacto** | > O status permite o [usuário](#l13-usuario) saber se os cartões estão atualizados ou não <br> > O status é atualizado pelo Guiabolso com as informações do banco do cartão |
| **Rastro** | Não possui |

### L18 - Meses futuros

| **L18** | **Meses futuros**  |
|--|--|
| **Versão**| Atual:1.2 (28/05) <br>Anterior: 1.1 (21/04)  |
| **Autor**| [Marcelo Araújo](https://github.com/santosm46) |
|**Classificação**| Objeto |
| **Sinônimos**| Economia planejada mensal |
| **Noção** | > O que está planejado de rendas e gastos totais mensalmente para o futuro|
| **Impacto** | > Informações dos meses futuros é atualizado pelo Guiabolso com informações cedidas pelo banco dos cartões <br> > Meses futuros podem ser alterados pelo [usuário](#l13-usuario) <br> > Auxilia o [usuário](#l13-usuario) a planejar-se financeiramente para os meses futuros |
| **Rastro** | [Cenário 10](../cenarios/#c10-solicitar-credito-pre-aprovado), [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L19 - Saúde financeira

| **L19** | **Saúde financeira**  |
|--|--|
| **Versão**| Atual: 1.1 <br> Anterior: [1.0]()|
| **Autor**| [Alan Lima](https://github.com/alanrslima) |
|**Classificação**| Estado |
| **Sinônimos**| -- |
| **Noção** | > Espécie de acompanhamento que informa o estado em que o [usuário](#l13-usuario) se encontra, financeiramente. <br> > Informa se o [usuário](#l13-usuario) está conseguindo controlar suas finanças como planejado.|
| **Impacto** | > A saúde financeira permite ao [usuário](#l13-usuario) visualizar e tomar decisões financeiras com mais segurança das consequências.<br> > A saúde financeira é atualizada conforme a movimentação das contas do [usuário](#l13-usuario).|
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L20 - Radar CPF

| **L20** | **Radar CPF**  |
|--|--|
| **Versão**| Atual: 1.1 <br> Anterior: [1.0]()|
| **Autor**| [Lucas Machado](https://github.com/lmmLucasMachado) |
|**Classificação**| Objeto |
|**Sinonimos**| Pesquisar CPF |
| **Noção** |> Funcionalidade presente na barra inferior do Guiabolso com fácil acesso; <br>> Busca informações de um determinado local e retorna um feedback para o [usuário](#l13-usuario)|
| **Impacto** | > Responsável por mostrar ao [usuário](#l13-usuario) informações relacionadas ao seu estado no Serasa <br> > Diz de forma simples e objetiva se o [usuário](#l13-usuario) possui pendências financeiras ou não|
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso), [Rich picture Radar CPF](../../pre-rastreabilidade/richpicture/#rp09-radar-cpf) |

### L21 - Extrato

| **L21** | **Extrato**  |
|--|--|
| **Versão**| Atual: 1.1 <br> Anterior: [1.0](#l21-extrato_1) |
| **Autor**| [Rafael Makaha](https://github.com/rafaelmakaha) |
|**Classificação**| Objeto |
|**Sinonimos**| -- |
| **Noção** | > Aba contida nas finanças do Guiabolso.<br> > Lista de rendas e gastos do mês atual, ou outro mês escolhido pelo [usuário](#l13-usuario). <br> > Inclui gráficos sobre os gastos e rendas.|
| **Impacto** | > O [usuário](#l13-usuario) recebe o feedback do fluxo de dinheiro de suas contas já registradas no GuiaBolso. <br> > Extrato é atualizado pelo Guiabolso com dados do banco ou do [usuário](#l13-usuario). <br> > Os meses futuros do extrato podem ser alterados pelo [usuário](#l13-usuario) <br> > Através do extrato, auxilía o [usuário](#l13-usuario) a planejar-se financeiramente para os meses futuros|
| **Rastro** | [ARG02 Extrato](../../pre-rastreabilidade/argumentacao/#arg02-extrato), [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L22 - Avaliação de Crédito

| **L22** | **Avaliação de Crédito**  |
|--|--|
| **Versão**| Atual: 1.2 <br> Anterior: [1.1](#l22-avaliacao-credito_1) |
| **Autor**| [Lucas Machado](https://github.com/lmmLucasMachado) |
|**Classificação**| Objeto |
|**Sinonimos**| Score |
| **Noção** | > Funcionalidade que mostra a pontuação do [usuário](#l13-usuario). <br> > Informando se o [usuário](#l13-usuario) tem pontuação boa ou ruim. <br> > Informação disponibilizada por instituições financeiras externas. |
| **Impacto** | > Através da avaliação de crédito, o [usuário](#l13-usuario) Guiabolso disponibiliza recomendações de empréstimo de acordo com a avaliação disponibilizada.<br> > A avaliação de crédito depende de agentes externos para realizar avaliação do [usuário](#l13-usuario). |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L23 - Meta

| **L23** | **Meta**  |
|--|--|
| **Versão**| 1.0 |
| **Autor**| [Leo Santos](https://github.com/leossb36) |
| **Classificação**| Objeto |
| **Sinônimos**| > Intuito <br> > Alvo <br> > Desígnio <br> > Escopo > <br> Objetivo <br> > Propósito. |
| **Noção** | > Um objetivo que se busca alcançar. <br> > A quantidade de dinheiro maxima que se quer economizar/gastar. |
| **Impacto** | > Metas são estabelecidas a fim de ter um controle de gastos para planejamentos futuros. |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L24 - Nome Limpo

| **L24** | **Nome Limpo**  |
|--|--|
| **Versão**| 1.0 |
| **Autor**| [Alan Lima](https://github.com/alanrslima) |
| **Classificação**| Objeto |
| **Sinônimos**| -- |
| **Noção** | > O [usuário](#l13-usuario) não deve a nenhuma empresa. <br> > O [usuário](#l13-usuario) não  possui cadastro em alguma instituição de proteção ao crédito. |
| **Impacto** | > [Usuário](#l13-usuario) com o nome limpo possui maior confiança para adquirir crédito. |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L25 - Crédito

| **L25** | **Crédito**  |
|--|--|
| **Versão**| Atual: 1.1 <br> Anterior: [1.0](#l25-credito_1) |
| **Autor**| [Lucas Machado](https://github.com/lmmLucasMachado) |
| **Classificação**| Objeto |
| **Sinônimos**| > Inadimplemente |
| **Noção** | > O [usuário](#l13-usuario) necessita de dinheiro. <br> > O Guiabolso diposnibiliza emprestimos com base na sua [avaliação](#l22-avaliacao-de-credito). |
| **Impacto** | > O crédito será disponibilizado com base na [avaliação](#l22-avaliacao-de-credito) de crédito do [usuário](#l13-usuario). <br> > Crédito possui uma quantidade de juros de acordo com a quantidade que foi solicitada. <br> > Porcentagem de juros de crédito é com base na [avaliação](#l22-avaliacao-de-credito) do [usuário](#l13-usuario). |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L26 - Chave de Segurança

| **L26** | **Chave de Segurança** |
|--|--|
| **Versão**| Atual: 1.1(23/03) <br> Anterior: [1.0](#l26-chave-de-seguranca_1) |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | Token, senha |
| **Noção** | > É uma senha ou conjunto de senhas para realizar [transações](../lexicos/#l30-transacao-bancaria) pelas plataformas online, [caixas](../lexicos/#l34-caixa-eletronico) de atendimento eletrônico, ou pelos aplicativos da [instituição financeira](#l31-instituicao-financeira); <br> > É gerada após o [indivíduo](#l39-individuo) inserir sua senha de acesso bancário(pin); <br> > Expira em segundos. |
| **Impacto** | > A chave de segurança garante a autenticidade do [indivíduo](#l39-individuo) que está fazendo uma [movimentação bancária](../lexicos/#l30-transacao-bancaria); <br> > A chave de segurança tem que ser usada rapidamente; <br> > A cada movimentação diferente é preciso uma chave de segurança difetente. | 
| **Rastro** | [Cenário 21](../cenarios/#c21-atualizar-contas-e-cartoes) |

### L27 - Cartão de débito 

| **L27** | **Cartão de débito** |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior:-- |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Objeto |
| **Sinônimos** | Despesa, À vista |
| **Noção** | > Modo de pagamento usando cartão; <br> > Pagamento feito à vista usando cartão, geralmente de um banco; |
| **Impacto** | > Ao comprar no débito o indivíduo sabe o valor gasto na hora; <br> > Ao se comprar no débito, o valor da [transação](#l30-transacao-bancaria) é descontado imediatamente do dinheiro do indivíduo; <br> > O indivíduo não pode parcelar uma compra feita no débito; <br> Ao comprar no débito o indivíduo passa a ter mais controle dos seus gastos; <br> > Ao comprar no débito o usuário pode ter um histórico de compras, a depender da [instituição financeira](#l31-instituicao-financeira) do cartão | 
| **Rastro**| Não possui (elicitado ao se fazer cenários) | 

### L28 - Cartão de crédito

| **L28** | **Cartão de crédito** |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior:-- |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Objeto |
| **Sinônimos** | À prazo, crediário |
| **Noção** | > Modo de pagamento usando cartão; <br> > Pagamento feito usando o cartão, que terá seu valor debitado *à posteriori*; |
| **Impacto** | > Ao comprar no crédito o indivíduo pode parcelar ou não a compra; <br> > Ao se comprar no crédito, o valor da [transação](#l30-transacao-bancaria) não é descontado imediatamente do dinheiro do indivíduo; <br> > O indivíduo pode parcelar uma compra feita no débito; <br> > Ao comprar no crédito o indivíduo pode acabar tendo um descontrole financeiro; <br> > Ao comprar no crédito o indivíduo pode pagar a compra em valores menores, permitindo a compra de um produto mais caro de forma suave | 
| **Rastro**| Não possui (elicitado ao se fazer cenários) | 

### L29 - Desconto 

| **L29** | **Desconto** |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior:-- |
| **Autor**| [Elias Bernardo](https://github.com/ebmm01) |
| **Classificação** | Objeto |
| **Sinônimos** | Corte, dedução, pechincha |
| **Noção** | > Redução no preço de um produto ou serviço; |
| **Impacto** | > O indivíduo que consegue um desconto paga preços menores em certos produtos; <br> > O desconto em contas permite que o usuário tenha uma maior ;[saúde financeira](#l19-saude-financeira) <br> > Compras com desconto permitem um menor [comprometimento de renda](#l7-comprometimento-de-renda) de um indivíduo; <br> > O desconto pode incentivar um indivíduo a gastar mais do que pode pagar, obrigando-o a reccorer à um empréstimo; | 
| **Rastro**| Não possui (elicitado ao se fazer cenários) | 

### L30 - Transação bancária 

| **L30** | **Transações bancárias** |
|--|--|
| **Versão**| Atual: 1.0(23/04) <br> Anterior:-- |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | Movimentação bancária, transferência |
| **Noção** | > Transferência de recursos fincanceiros de uma [conta bancária](#l33-conta-bancaria) a outra entre pessoas físicas ou jurídicas; <br> > Troca de recursos financeiros em ambientes bancários([caixa eletônico](#l34-caixa-eletronico), [Internet Banking](#l16-internet-banking) |
| **Impacto** | > Para realizar uma transação bancária, não é preciso movimentar dinheiro em espécie, sendo mais segura; <br> > Se a transação bancária ocorrer entre [bancos](#l31-instituicao-financeira) distintos, há uma taxa a ser paga pela realização do procedimento; <br> > Uma transação bancária pode sair mais cara do que uma movimentação em espécie. | 
| **Rastro**| [L14](#l14-transacoes-ignoradas) e [L26](#l26-chave-de-seguranca) | 

### L31 - Instituição financeira 

| **L31** | **Instituição financeira** |
|--|--|
| **Versão**| Atual: 1.0(23/04) <br> Anterior:-- |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | banco, financeira, corretora de valores |
| **Noção** | > Intermediária entre um [indivíduo](#l39-individuo) e algum tipo de serviço financeiro; <br> > Organização que otimiza a alocação de capitais financeiros; |
| **Impacto** | > Para uma instituição financeira cuidar do seu capital, é preciso deixá-lo a disposição dela; <br> > Instituição financeira pode financiar compra de bens; <br> > Para obter serviços ofericidos por uma instituição financeira é preciso pagar taxas; <br> > Instituições financeiras podem oferecer empréstimos ou [crédito](#l25-credito); <br> > Instituição financeira pode itermediar investimentos. |
| **Rastro**| [Cenário 22](../cenarios/#c22-contratar-emprestimo) | 

### L32 - Guia

| **L32** | **Guia** |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior:-- |
| **Autor**| [Marcelo Araújo](https://github.com/santosm46) |
| **Classificação** | Objeto |
| **Sinônimos** | Aba guia , Dicas |
| **Noção** | > Onde é mostrado conselhos financeiros, anúncios de patrocinadores e publicações de sites de patrocinadores; <br> > Tem informações sobre a situação financeira do [usuário], como por exemplo, comparação do gasto do mês atual com o anterior. |
| **Impacto** | > Aba guia informa o [usuário] sobre comparações e informações de suas finanças; <br> > Guiabolso recebe dinheiro por publicar na aba guia anúncios de patrocinadores.|
| **Rastro**| [Rich picture guia](../../pre-rastreabilidade/richpicture/#rp07-aba-guia) |

### L33 - Conta bancária

| **L33** | **Conta bancária** |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior:-- |
| **Autor**| [Marcelo Araújo](https://github.com/santosm46) |
| **Classificação** | Objeto |
| **Sinônimos** | Conta de banco |
| **Noção** | > Cadastro de um banco que foi conectado ao Guiabolso pelo [usuário]; <br> > Contém informações da conta bancária. |
| **Impacto** | > Conta bancária é atualizada pelo Guiabolso com o banco do cartão; <br> > Conta bancária fornece ao [usuário] feedback de seu [extrato](#l21-extrato) e situação no banco.|
| **Rastro**| [Rich picture Aba de finanças](../../pre-rastreabilidade/richpicture/#rp06-financeiro-aba) |

### L34 - Caixa Eletrônico

| **L34** | **Caixa Eletrônico** |
|--|--|
| **Versão**| Atual: 1.0(23/04) <br> Anterior:-- |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | Caixa automático, terminal bancário |
| **Noção** | > Equipamento de automação bancária; <br> > Oferece serviços bancários de forma automática. |
| **Impacto** | > O caixa eletrônico não precisa de um funcionário do [banco](#l31-instituicao-financeira) para ser usado; <br> > As pessoas podem sacar ou depositar dinheiro no caixa eletrônico, além de visualizar suas [contas bancárias](#l33-conta-bancaria) |
| **Rastro**| [Cenário 10](../cenarios/#c10-solicitar-credito-pre-aprovado) | 

### L35 - Suporte 

| **L35** | **Suporte** |
|--|--|
| **Versão**| Atual: 1.0(32/04) <br> Anterior:-- |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | atendimento, assistência |
| **Noção** | > Serviço de auxílio ao [usuário](#l13-usuario); <br> > Assistência ao [usuário](#l13-usuario) quando este estiver com dififuldades ou dúvida. |
| **Impacto** | > O usuário precisa do suporte quando encontra alguma dificuldade no uso do sistema; <br> > O usuário precisa de suporte quando encotra uma falha no sistema; <br> > O suporte é essencial para a comunicação entre empresa e cliente; <br> > O suporte deve está sempre disponível para o [usuário](#l13-usuario). |
| **Rastro**| [Cenário 11](../cenarios/#c11-solicitar-suporte) | 

### L36 - Agenda 

| **L36** | **Agenda** |
|--|--|
| **Versão**| Atual: 1.0(23/04) <br> Anterior:-- |
| **Autor**| [Sara Silva](https://github.com/silvasara) |
| **Classificação** | Objeto |
| **Sinônimos** | programação, planejamento de pagamentos |
| **Noção** | > Planejamento de dias x pagamentos; <br> > Organização de tarefas; <br> > Organização de contas a pagar; |
| **Impacto** | > No Guiabolso, a agenda pode ser usada para se lembrar quais dias de pagamentos das contas; <br> > A agenda ajuda o usuário a não esquecer das contas e fica endividade; <br> > A agenda ajuda o usuário a se [planejar financeiramente](#l40-planejamento-financeiro). |
| **Rastro**| [Cenário 23](../cenarios/#c23-adicionar-na-agenda) | 

### L37 - Lançamentos futuros

| **L37** | **Lançamentos futuros**  |
|--|--|
| **Versão**| Atual: 1.0 (27/04/19) <br> Anterior: - | 
| **Autor**| [Shayane Alcântara](https://github.com/shayanealcantara) |
| **Noção** | > Quando está previsto que um [usuário](l13-usuário) pessoa irá receber alguma [renda](#l28-renda); <br> > [Renda](#l28-renda) de entrada ou saída agendada com data futura;<br> > Pagamentos já realizados pela [empresa](#l31-instituicoes-financeiras) ou pessoa específica que ainda não está disponível para uso ou presente no seu [extrato](#l21-extrato); <br> > Quando o [usuário](l13-usuário) deseja saber o andamento de alguma [renda](#l28-renda). | 
|**Sinônimos**| <br> > [Renda](#l28-renda) que irá ser retirada ou adicionada da conta do [usuário](l13-usuário) no futuro.
| **Impacto** | > O [usuário](#l13-usuario) acessa o [extrato](#l21-extrato) para visualizar os lançamentos futuros. <br> > A visualização dos lançamentos futuros permite organização ([planejamento](#l40-planejamento-financeiro)) e transparência para o [usuário](#l13-usuario).|
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L38 - Renda

| **L38** | **Renda**  |
|--|--|
| **Versão**| Atual: 1.0 (27/04/19) <br> Anterior: - | 
| **Autor**| [Shayane Alcântara](https://github.com/shayanealcantara) |
| **Classificação**| Objeto |
|**Sinônimos**| <br> > Ferramenta comercial para movimentar mercado financeiro; <br> > Dinheiro; <br> > Moeda; <br> > Cheque, etc.|
| **Noção** | > Quando há a necessidade ou vontade de adquirir algo usa esta forma; <br> > Quando o [usuário](#l13-usuario) trabalha ou realiza alguma movimentação comercial, ele recebe uma gratificação; <br> > Quando o usuário faz compras no [cartão de crédito](#l28-cartao-de-credito), deve pagar com dinheiro no final das contas. | 
| **Impacto** | > O [usuário](#l13-usuario) recebe renda mensal ao realizar algum [serviço comercial](#l42-transacao); <br> > A renda que o usuário deve ou ganha, aparecem no [extrato](#l21-extrato); <br> > Ao usar o Guiabolso, o [usuário](#l13-usuario) deve informar sua renda mensal para criar [planejamento](#l40-planejamento-financeiro).|
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso)|

### L39 - Indivíduo

| **L39** | **Indivíduo**  |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior: - | 
| **Autor**| -- |
| **Classificação** | Objeto |
| **Sinônimos** | Pessoa |
| **Noção** | > Pessoa qualquer, usuária ou não do Guiabolso; <br> > Pessoa alheia ou não ao universo da aplicação; | 
| **Impacto** | > O Indivíduo pode se tornar um [usuário](#l13-usuario) do Guiabolso; <br> > Um indivíduo pode ser alheio ao aplicativo, sem nem ao menos conhecer  Guiabolso; |
| **Rastro** |  Não há |

### L40 - Planejamento financeiro

| **L40** | **Planejamento financeiro**  |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior: - | 
| **Autor**| -- |
| **Classificação** | Objeto |
| **Sinônimos** | Administrar, gerenciar |
| **Noção** | > Gerenciar o dinheiro de forma que todos os gastos e rendas já sejam conhecidos; | 
| **Impacto** | > Um bom planejamento financeiro permite que um [indivíduo](#individuo); <br> > Um indivíduo pode ser alheio ao aplicativo, sem nem ao menos conhecer  Guiabolso; |
| **Rastro** |  Não há |


### L41 - Dados bancários

| **L41** | **Dados bancários**  |
|--|--|
| **Versão**| Atual: 1.0 |
| **Autor**| [Leo Santos](https://github.com/leossb36) |
| **Classificação**| Objeto |
|**Sinônimos**|Informações de uma [conta] no banco|
| **Noção** | >	Quando uma pessoa cria uma [conta] em um banco <br> >	Informações que irão identificar uma [conta] bancária <br> >	Associa uma pessoa a uma [conta] bancária que seja dela|
| **Impacto** | > Um indivíduo que possui dados bancários, possue uma [conta] em um banco <br> > Dados bancários são utilizados para transações entre contas de indivíduos|
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |


### L42 - Transação

| **L42** | **Transação**  |
|--|--|
| **Versão**| Atual: 1.0 |
| **Autor**| [Alan Lima](https://github.com/alanrslima) |
| **Classificação**| Objeto |
|**Sinônimos**|Operação, ato, processo, transferência, Troca|
| **Noção** | > Produto de uma movimentação de dinheiro <br> > Ato de compra, venda, empréstimo <br> > Troca de bem ou serviço por alguma quantidade de dinheiro|
| **Impacto** | <br> >	[Usuário] realiza uma compra no supermercado <br> > [Usuário] realiza um depósito em outra [conta] <br> > [Usuário] recebe dinheiro de volta após uma compra|
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L43 - Emprestimo

| **L43** | **Emprestimo**  |
|--|--|
| **Versão**| Atual: 1.0 |
| **Autor**| [Lucas Machado](https://github.com/lmmLucasMachado) |
| **Classificação**| Objeto  |
|**Sinônimos**| Crediario, prazo |
| **Noção** | > O ​usuário​ necessita de dinheiro.  <br>> O Guiabolso disponibiliza empréstimos com base na sua ​avaliação.|
| **Impacto** |  > O [​usuário​] recebe o empréstimo e pode fazer o que desejava antes. <br>> O [​usuário] consegue o dinheiro necessário para efetuar os seus planos 
| **Rastro** | não possui |

## Versões anteriores

### L1 - Nome Sujo

| **L1** | **Nome Sujo**  |
|--|--|
| **Versão**| 1.0 | 
| **Noção** | > Quando uma pessoa possui nome sujo no serasa <br> > O nome da pessoa está no cadastro da dívida ativa de órgãos de cobrança <br> > Status da pessoa que não honra com suas dívidas | 
| **Impacto** | > O [usuário](#l13-usuario) com o nome sujo não faz empréstimos <br> > O [usuário](#l13-usuario) com o nome sujo não consegue contratar alguns serviços <br> > Operadoras de cobrança ligam constantemente para o [usuário](#l13-usuario) com o nome sujo |

### L2 - Cadastro positivo

| **L2** | **Cadastro Positivo**  |
|--|--|
| **Versão**| Atual: 1.0 (27/04/19) <br> Anterior: - | 
| **Autor**| [Shayane Alcântara](https://github.com/shayanealcantara) |
| **Noção** | > Quando uma pessoa não possui dívidas ou com o [nome limpo](#l24-nome-limpo); <br> > Pessoa no cadastro de "Bom pagador"; <br> > Pessoa que quer bem visto pelas [instituições](#l31-instituicoes-financeiras); <br> > Quando uma pessoa quer ser vista não só pelas dívidas no seu nome [limpo](#l24-nome-limpo) ou [sujo](#l1-nome-sujo), mas pelo seus hábitos financeiros; <br> > Quando uma pessoa quer que seu nome [limpo](#l24-nome-limpo) ou [sujo](#l1-nome-sujo) seja visto positivamente ao ser consultado por empresas. | 
|**Sinônimos**| <br> > Empresas verem o usuário de forma positiva; <br> > Boa reputação no mercado.
| **Impacto** | > O [usuário](../lexicos/#l13-usuario) que está no cadastro positivo tem maior facilidade de fazer empréstimos; <br> > O indivíduo que está no cadastro positivo tem uma maior [linha de crédito](#l22-avaliacao-de-credito); <br> > O indivíduo que está no cadastro positivo consegue juros menores em certas [operações bancárias](#l42-transacao). |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L4 - Score do Serasa

| **L4** | **Score do Serasa**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Pontuação numérica que classifica economicamente uma pessoa <br> > Chance percentual de um indivíduo não pagar uma conta | 
| **Impacto** | > Um indivíduo com o score do serasa alto tem o cadastro positivo aceito <br> > Um indivíduo com o score do serasa baixo tem uma chance alta de estar com o nome sujo <br> > Um indivíduo com o score do serasa baixo tem dificuldade em conseguir um crédito pré-aprovado |

### L5 - Dívida ativanome s

| **L5** | **Dívida Ativa**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Inserção do nome de um indivíduo com o status de nome sujo no cadastro de devedores dos serviços de proteção de crédito <br> > Estar com o nome sujo | 
| **Impacto** | > Um [usuário](#l13-usuario) que está na dívida ativa tem seu score do serasa reduzido <br> > Um [usuário](#l13-usuario) que está na dívida ativa tem uma redução de linhas de crédito |

### L6 - Crédito Pré-aprovado

| **L6** | **Crédito Pré-aprovado**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Valor em dinheiro disponibilizado por instituições financeiras para um indivíduo resgatar a qualquer momento <br> > Dinheiro disponibilizado através de uma análise prévia feita por bancos e [instituições](../lexicos/l31-instituicao-financeira) financeiras | 
| **Impacto** | > Ao resgatar o crédito pré-aprovado, um indivíduo estará fazendo uma dívida <br> > Ter um crédito pré-aprovado alto significa ter uma boa análise de crédito e score do serasa |

### L7 - Comprometimento de renda

| **L7** | **Comprometimento de renda**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Quando um indivíduo tem parte do seu dinheiro já destinado à algum gasto <br> > Indivíduo com uma dívida que reduz seu salário bruto | 
| **Impacto** | > Um indivíduo com a renda comprometida tem dificuldades em gerenciar seu dinheiro <br> > Um indivíduo com a renda comprometida não possui um bom crédito pré-aprovado <br> > Um indivíduo com a renda comprometida pode não conseguir um empréstimo |

### L8 - Simulação

| **L8** | **Simulação**  |
|--|--|
| **Versão**| 1.0 | 
| **Noção** | > Fazer um empréstimo fantasioso <br> > Fingir fazer um empréstimo para saber as condições e consequências |
| **Impacto** | > Um indivíduo faz uma simulação, conhecendo valores e prazos de um empréstimo <br> > Após fazer a simulação  indivíduo pode optar por contratar ou não o seu crédito pré-aprovado <br> > Fazendo um empréstimo após uma simulação, um indivíduo passar a ter parte da sua renda comprometida |

### L10 - Pausar cartão

| **L10** | **Pausar cartão**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Impedir que o aplicativo atualize os dados (gastos e/ou pagamentos) de determinado cartão <br> > Fazer com que um cartão não seja atualizado dentro do Guiabolso, temporariamente |
|**Classificação**| Verbo |
| **Impacto** | > Ao pausar um cartão, o [usuário](/#l13-usuario) não terá mais uma gerência de gastos dele |

### L14 - Transações ignoradas

| **L14** | **Transações ignoradas**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Movimentações na conta que o [usuário](#l13-usuario) deseja ignorar. |
| **Impacto** | > Transações ignoradas não são rastreadas nos gastos; <br> > Com algumas transações sendo ignoradas, o [usuário](#l13-usuario) pode dar mais atenção a transações que considera mais importantes; <br> > O [usuário](#l13-usuario) pode se esquecer de que um determinado gasto está como transação ignorada e atrapalhar seu planejamento financeiro. |

### L15 - Crediário

| **L15** | **Crediário**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Forma de financiamento de bens e serviços; <br> > Parcelamento em carnê; | 
| **Impacto** | > As parcelas do crediário são fixas acrescidas de juros e correção monetária; <br> > Fazendo o crediário, o indivíduo sai do estabelecimento sabendo exatamente quanto pagará e a data de vencimento de cada parcela; <br> > O crediário permite parcelamento em até 48x, facilitando a perda de controle de boletos e o endividamento; <br> > Fazer um crediário é fazer [comprometimento de renda](#l7-comprometimento-de-renda) a longo prazo. |

### L16 - Internet Banking

| **L16** | **Internet Banking**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Ambiente bancário na Internet; <br> > Site com alto nível de segurança onde ficam disponíveis serviços oferecidos pelos bancos; <br> > Acesso ao serviços bancários pelo computador/navegador. |
| **Impacto** | > O Internet Banking evita o descolocamento até agência bancária ou caixa eletrônico <br> > Por vezes, é necessária a instalação de plugins de segurança para que o Internet Banking seja usado. |

### L17 - Status

| **L17** | **Status**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Mostra a situação da conta do(s) cartão / cartões <br> > Diz se as informações sobre transações do cartão estão atualizadas|
| **Impacto** | > Informa o estado do cartão ( atualizado / não atualizado) <br> > É atualizado pelo Guiabolso junto com o banco do cartão |

### L18 - Meses futuros

| **L18** | **Meses futuros**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Mostra planejamento de rendas e gastos totais de cada mês <br> > Mostra rendas e gastos que estão  planejados para os meses seguintes|
| **Impacto** | > É atualizado pelo Guiabolso junto com o banco dos cartões <br> > pode ser adicionado rendas e gastos pelo [usuário](#l13-usuario)<br> > pode ser alterado pelo [usuário](#l13-usuario)|


### L21 - Extrato

| **L21 ** | **Extrato**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Aba contida nas finanças do Guiabolso;<br> > Lista de rendas e gastos do mês atual, ou outro mês escolhido pelo [usuário](#l13-usuario). <br> > Inclui gráficos sobre os gastos e rendas.|
| **Impacto** | > O [usuário](#l13-usuario) recebe o feedback do fluxo de dinheiro de suas contas já registradas no GuiaBolso;|

### L22 - Avaliação de Crédito

| **L22** | **Avaliação de Crédito**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Funcionalidade que mostra a pontuação do [usuário](#l13-usuario) em relação aos dados no SERASA, informando se o [usuário](#l13-usuario) tem pontuação boa ou ruim.|
| **Impacto** | > Mostra o resultado da avaliação do [usuário](#l13-usuario) para ou não realizar um empréstimo, seja através do Guiabolso ou em agência bancária. |

### L25 - Crédito

| **L25** | **Crédito**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > O [usuário](#l13-usuario) necessita de dinheiro. <br> > Com base em uma confiança e emprestado alguma quantidade de dinheiro. |
| **Impacto** | >A pessoa recebe a quantidade de dinheiro que solicitou. |

### L26 - Chave de Segurança

| **L26** | **Chave de Segurança**  |
|--|--|
| **Versão**| Atual: 1.0 |
| **Noção** | > É uma senha ou conjunto de senhas para realizar transações pelas plataformas online, caixas de atendimento eletrônico, ou pelos aplicativos da instituição financeira; <br> > É gerada após o indivíduo inserir sua senha de acesso bancário(pin); <br> > Expira em segundos. |
| **Impacto** | > A chave de segurança garante a autenticidade do indíviduo que está fazendo uma movimentação bancária; <br>> A chave de segurança tem que ser usada rapidamente; <br> > A cada movimentação diferente é preciso uma chave de segurança difetente. |  



[usuário]: ../lexicos/#l13-usuario
[usuários]: ../lexicos/#l13-usuario
[Usuários]: ../lexicos/#l13-usuario
[Usuário]: ../lexicos/#l13-usuario
[conta]: ./#l33-conta-bancaria
