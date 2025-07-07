# Desafio ONE - TelecomX
Repositório para armazenar o challenge de análise do churn da empresa Telecom X

# Descrição
A Telecom X é uma empresa de telecomunicações, e você foi contratado como assistente de análise de dados para fazer parte da equipe de Data Science. A equipe está com um novo projeto denominado Churn de Clientes.

A empresa vem sofrendo alto índice de evasão de clientes, porém, eles não conseguem descobrir o porquê disso estar acontecendo. E é aí que você entra como assistente de análise de dados. Você ficará responsável por uma das partes mais importantes da análise de dados. Você ficará responsável por buscar, tratar e realizar uma análise exploratoria dos dados da empresa.

# Etapas
Efetuei as etapas de extração, transformação, análise e preparação das variáveis antes de iniciar o processo de modelagem, como descrito no notebook do projeto.

Para avaliar a capacidade das informações disponíveis de explicarem ou preverem o churn, eu fiz um modelo simples por regressão linear e e medi a força das variáveis pelos valores Shap.

# Resultados
Através do processo acima, obtemos um modelo de capacidade preditiva boa (KS maior que 50), o que dá confiança aos resultados.

A variável mais explicativa do Churn é a Tenure, contínua, que possui uma correlação de -35%. Depois dela, as mais importantes são:
* Serviço de internet
* método de pagamento
* contrato
* pagamento sem papel
* suporte técnico
* segurança online
* senioridade
* dependendes
