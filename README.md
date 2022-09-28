# Análise de Origem de Leads

Este notebook apresenta uma análise dos dados de negócio fictícios de uma empresa de treinamentos online, a qual captura dados de seus potenciais clientes através de formulários em seu site, redes sociais e anúncios.

Essa empresa consegue exportar um arquivo de extensão `.txt` que lista os e-mails de seus _leads_ e a respectiva origem de cada um deles.

Podemos descobrir a origem de um _lead_ através de um prefixo no link através do qual a pessoa se inscreveu. Na tabela a seguir temos a descrição dos prefixos e a origem a que cada um se refere:

<br>

| IDENTIFICADOR    | ORGÂNICO | ORIGEM             |
| :--------------- | :------: | :----------------- |
| hashtag_site_org |   SIM    | Site               |
| hashtag_yt_org   |   SIM    | YouTube            |
| hashtag_ig_org   |   SIM    | Instagram          |
| hashtag_igfb_org |   SIM    | Instagram/Facebook |

<br>

O objetivo da análise é encontrar respostas para as seguintes perguntas:

1. Quantos alunos vieram através de anúncios?

2. Quanto alunos chegaram até a empresa organicamente?

3. Qual é a melhor fonte orgânica de alunos?

Obs: todas as fontes são orgânicas, exceto os anúncios.

## Exibição dos Resultados

Com as respostas dessas perguntas em mãos, criamos um arquivo intitulado `Relatório - Indicadores de Origem de Leads.txt` para exibir os resultados de nossa análise.
