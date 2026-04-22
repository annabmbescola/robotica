# robotica


A inteligência artificial é muito útil no nosso dia a dia e na criação de projetos, porém, em algumas situações ela não é eficiente para uso. Portanto existem os malefícios gerado atráves dela.
A IA acelera a criação, o uso sem revisão em robótica traz riscos graves. Primeiro, no hardware (físico), ela pode sugerir ligações elétricas erradas ou componentes incompatíveis, o que causa curto-circuitos e danos físicos ao equipamento.
No software, o código gerado costuma ser instável ou conter bugs. Isso resulta em comportamentos imprevisíveis do robô, gerando riscos de acidentes e ferimentos, já que a máquina interage com o mundo real.
Por fim, o prejuízo intelectual. A dependência da IA impede que você aprenda a lógica fundamental, tornando impossível identificar e consertar erros manualmente quando a ferramenta falha. Para segurança, a IA deve ser apenas uma assistente, nunca a decisão final.


cm cria um projeto de robotica com ia 


Hoje o dia foi de botar a mão na massa na Aula 1 e começamos a detalhar o nosso projeto: um semáforo inteligente com travessia de pedestres. Eu e as meninas nos unimos para criar um sistema que prioriza a segurança, onde o sinal fica aberto para os carros, mas responde prontamente quando alguém precisa atravessar.
Para tirar a ideia do papel, usamos alguns materiais essenciais e foi bem legal entender o papel de cada um:
Arduino: É o "cérebro" do nosso projeto, onde gravamos o código para controlar tudo.
LEDs (Verde, Amarelo e Vermelho): São as luzes que sinalizam o trânsito tanto para os motoristas quanto para os pedestres.
Resistores: Usamos para proteger os LEDs e não deixar que eles queimem com a corrente elétrica.
Botão (Push button): É o comando do pedestre; quando apertado, envia o sinal para o Arduino interromper o trânsito.
Jumpers: São os cabinhos coloridos que usamos para conectar todos os componentes entre si e na placa.
Protoboard: Aquela placa cheia de furinhos que permite a gente montar o circuito sem precisar soldar nada.
Sensor IR (Infravermelho): Ele detecta movimento ou presença através de luz infravermelha, ajudando o sistema a ser ainda mais inteligente.
No código, o grande destaque foi o uso do attachInterrupt. Com isso, conseguimos fazer com que o Arduino entenda o comando do botão na hora. No dia a dia do projeto, ele funciona assim: enquanto ninguém aperta o botão, os carros seguem no verde e os pedestres esperam no vermelho.
Assim que o botão é acionado, nossa sequência entra em ação: o amarelo brilha por 3 segundos, o sinal fecha para os veículos e o verde abre para os pedestres por 5 segundos. Para ninguém ser pego de surpresa, colocamos o LED para piscar avisando que o tempo está acabando antes de voltar ao normal.
Ficamos muito orgulhosas do resultado em grupo! O código ficou organizado e a montagem bem segura.
