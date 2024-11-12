# RS_UHI_2023_Castanhal-PA

Código utilizado para artigo enviado para o SBSR 2025: "Análise de Índices Espectrais e Temperatura da Superfície para Estudo do Impacto da Urbanização nas Ilhas de Calor em Castanhal-PA"

Etapas:
* Obtenção de Imagem Mediana de 2023 do Landsat-8 na área de interesse pelo Google Earth Engine
* Calculo da Temperatura de Superfície (LST), Índice Melhorado de Vegetação (EVI) e Índice de Urbanização (UI)
* Obtenção da Classificação de Uso e Cobertura do Solo por MapBiomas
* Transformação da Imagem para Dataframe e Amostragem de pontos em quatro classes de solo
* Geração dos Mapas de Índices Espectrais
* Análise da Relação Estatística da LST com os Índices EVI e UI
