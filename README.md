# datasets_Twitter_Lula_Bolsonaro

Incluem-se aqui os Tweet postados diretamente pelas contas dos candidatos Lula e Bolsonaro no primeiro semestre de 2022, totalizando 1461 e 1342 Tweets, respectivamente.

Este repositório é parte de um projeto de pesquisa ainda em revisão, do programa de MBA em Análise de Dados e Analystics USP-Esalq. 
A fim de facilitar a reprodutibilidadee fomenta novos trabalhos, o dataset construído é oferecido publicamente. 

Interessado em saber mais ou em alguma parceria científica? Fique a vontade para falar comigo: 
E-mail: cbnfreitas@gmail.com , Twitter: @cbnfreitas1

Acabei não tendo tempo de detalhar como rodar o script! Deixo abaixo algumas dicas que talvez sejam úteis:

1. Você precisa de uma forma de ler o Jupyter Notebook. Acho que a forma mais fácil é via Anaconda (https://docs.anaconda.com/ae-notebooks/user-guide/basic-tasks/apps/jupyter/index.html). Alternativamente, acho que dá pra fazer tudo online no Google Colab (https://colab.research.google.com/)
1. Acho que o Anaconda já traz todas as dependências. Caso contrário, será necessário instalar os imports que estiverem faltando (pip install requests, por exemplo).
1. Depois disso, você vai precisar ter uma chave de acesso para a API do Twitter (API Key). É necessário solicitar no site e esperar alguns dias para eles responderem, mas acho que continua de graça: https://developer.twitter.com/en/docs/twitter-api/getting-started/getting-access-to-the-twitter-api . Essa API você vai colocar na Jupyter nessa linha aqui: BEARER_TOKEN = config.BEARER_TOKEN. (Não precisa usar o dotenv)
1. No mais, não é garantia que o script irá rodar da mesma forma... Pode ser que a API tenha mudado algum parâmetro, daí você precisa debugar mesmo.
1. Deixo em anexo a apresentação e o texto como referências.[TCC - MBA USP ESALQ_dia_19_out.docx](https://github.com/cbnfreitas/datasets_Twitter_Lula_Bolsonaro/files/11154090/TCC.-.MBA.USP.ESALQ_dia_19_out.docx)
[Celso - Twitter - Usp Esalq - MBA - Template.pptx](https://github.com/cbnfreitas/datasets_Twitter_Lula_Bolsonaro/files/11154092/Celso.-.Twitter.-.Usp.Esalq.-.MBA.-.Template.pptx)
