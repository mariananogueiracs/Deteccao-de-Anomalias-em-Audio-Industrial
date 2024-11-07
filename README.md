# Detecção de Anomalias em Áudio Industrial

Seminário da disciplina de Processamento Digital de Sinais e Imagens, ministrada pelo professor Aldo Díaz.

<img src="https://github.com/user-attachments/assets/82877474-1c77-4966-9580-bffd18867913" alt="header" width="1000" height="400"/>


## Autores

+ Andriel de Figueredo Furtado
+ Anna Pietra Vitória León Bastos Moreira
+ Maria Carolina Xavier de Almeida
+ Mariana Nogueira Carvalho da Silveira
+ Rosimeire Alves da Silva

## Resumo

Com o avanço da Indústria 4.0 e das *Smart Factories*, a integração de tecnologias para monitoramento contínuo e manutenção preditiva torna-se relevante para evitar paradas inesperadas e otimizar as operações industriais. Sons anômalos emitidos por ventiladores industriais podem indicar possíveis falhas. Nesse contexto, o trabalho propõe o desenvolvimento de uma ferramenta que, por meio de processamento de sinais e aprendizado de máquina, seja capaz de identificar esses sons, contribuindo para uma manutenção mais eficiente. A validação da abordagem será realizada com o uso do dataset MIMII (*Malfunctioning Industrial Machine Investigation and Inspection*), permitindo a classificação de sons normais e defeituosos dos ventiladores industriais.


Palavras-chave: detecção de anomalias; classificação de áudio; processamento de sinais; aprendizado de máquina.


## Introdução

Fábricas inteligentes já utilizam a detecção de anomalias (eventos incomuns) para diminuir a perda na qualidade dos produtos fabricados, detecção de deterioramento de equipamentos, dar continuidade e confiabilidade aos processos industriais, redução de custos, melhorar as condições de segurança dos trabalhadores e aumentar a eficiência e eficácia dos processos industriais. Porém, é difícil a detecção de anomalias em eventos sonoros devido à sobreposição de sons no pátio industrial, portanto revisaremos métodos de aprendizagem profunda usando redes neurais para detecção de anomalias e eliminação de ruídos para manutenção preditiva.
Atualmente, os principais avanços da área baseiam-se especialmente em deep learning (DL), utilizando Convolutional Neural Networks (CNNs) para dados de imagens de espectrogramas e Recurrent Neural Networks (RNNs) para dados de séries temporais. Ciaburro et al [5] propõe uma metodologia inovadora para diagnóstico de falhas em ventiladores industriais, focando na detecção de depósitos de poeira nas pás de ventiladores axiais. A metodologia emprega a aquisição de emissões acústicas e técnicas de aprendizado profundo, especificamente redes neurais convolucionais (CNNs), para identificar automaticamente as condições de operação do ventilador. O estudo compara duas condições operacionais: uma sem falhas, com pás limpas, e outra com falhas, onde depósitos artificiais de poeira foram adicionados. Utilizando a técnica de Transfer Learning sobre a rede SqueezeNet pré-treinada, o modelo mostrou excelente desempenho, alcançando uma precisão de 95% na classificação das condições operacionais. Tang et al. [6] indica que as técnicas de DL têm alcançado precisão superior em diagnósticos, proporcionando capacidade de extração de características complexas dos sinais de falha sem necessidade de intervenção humana intensiva. Em aplicações práticas, essas abordagens mostraram-se eficazes na identificação de falhas com altas taxas de precisão, especialmente em condições de trabalho não estacionárias e em sistemas de difícil acesso. O sistema de Shubita et. al [7] alcança uma precisão comparável aos estudos existentes, mas com uma abordagem simplificada e otimizada para execução em dispositivos com recursos limitados. Essa metodologia oferece uma solução prática para monitoramento contínuo de máquinas em ambientes industriais, podendo ser expandida para outros tipos de falhas e condições operacionais com ajustes no hardware e nas técnicas de processamento. Por fim, Barreto et. al [8] propõe um sistema de detecção de falhas em transportadores de correia na mineração usando aprendizado de máquina (ML) aplicado a dados de vibração. Após o pré-processamento e extração de características especializadas dos sinais, o modelo XGBoost obteve o melhor desempenho, com ROC AUC de 91% e baixa taxa de falsos positivos (23%). Os resultados mostram que características especializadas aumentam a precisão do modelo, indicando a eficácia do ML no monitoramento preditivo em ambientes industriais desafiadores.


## Revisão Bibliográfica

A Detecção de Anomalias (AAD) em máquinas industriais visa encontrar interpretações de sinais sonoros, isolando áudios normais dos anômalos. O aprendizado de máquina supervisionado utiliza um classificador de sons normais enquanto no aprendizado de máquina não supervisionado usa-se a técnica do "autoencoder" para remover ruídos e compactar os dados.[1]
O dataset MIMII (Malfunctioning Industrial Machine Investigation and Inspection) é um conjunto de dados sonoros de máquinas industriais,válvulas, bombas, ventiladores e trilhos deslizantes, com sete modelos de produtos individuais com sons normais e anômalos com ruídos misturados aos sons das máquinas. Os sons foram registrados por um conjunto de microfones de oito canais com taxa de amostragem de 16 kHz e 16 bits por amostra para diagnosticar falhas baseada em sons e disponibilizado pela Hitachi, Ltd. sob uma licença Creative Commons.[2]
O modelo de rede neural, autocodificador-decodificadora, relacionando pré-processamento de dados com funções de custo para estimativas de estado , projetados com filtros adaptativos têm desempenho melhor quando comparados com técnicas classificatórias de dados ruidosos[3]
O método MFCC (Mel Frequency Cepstral Coefficients) detecta anomalias em áudios reais que foram misturados à sons artificiais, apesar de incidir muito ruído serve para aplicar análise com o algoritmo PCA (Principal Component Analysis) para propor detecção de sons consistentes em eventos conectados a explosões ambientais.[4]


## Fundamentos Teóricos


## Metodologia


## Resultados 


## Conclusões


## Referências

