Avaliação dos Resultados do Modelo
Análise das Predições:
Mensagem: 'Quero consultar quanto dinheiro tenho'

Intenção Predita: [fazer_pix]
Avaliação: Incorreto. A intenção correta para 'Quero consultar quanto dinheiro tenho' deveria ser consultar_saldo. O modelo associou erroneamente a frase à intenção de 'fazer_pix'. Isso pode indicar que o modelo não capturou adequadamente os termos relacionados à consulta de saldo, ou que as frases de treinamento para 'consultar_saldo' eram muito limitadas e não cobriam essa variação.
Mensagem: 'Pode me ajudar a fazer um pix?'

Intenção Predita: [fazer_pix]
Avaliação: Correto. A intenção predita está alinhada com o significado da mensagem, demonstrando que o modelo conseguiu identificar corretamente a intenção de realizar um PIX.
Mensagem: 'Gostaria de cancelar meu cartão de crédito'

Intenção Predita: [cancelar_conta]
Avaliação: Incorreto (com ressalvas). Embora a ação seja de cancelamento, a predição cancelar_conta é genérica demais para 'cancelar meu cartão de crédito'. Idealmente, se o sistema fosse mais robusto, haveria uma intenção específica como cancelar_cartao. Dada a limitação do dataset de treinamento, que possui apenas a intenção cancelar_conta, o modelo optou pela categoria mais próxima. No entanto, para um sistema em produção, essa seria uma predição imprecisa que poderia levar a uma ação errada.
