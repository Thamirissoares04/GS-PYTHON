VerdiHome - Monitoramento de Consumo de Energia e Análise de Fontes Renováveis
Este código tem como objetivo calcular o consumo de energia diário de aparelhos domésticos, sugerir formas de economia e analisar a viabilidade do uso de fontes de energia renováveis (solar e eólica) para cobrir esse consumo.

Visão Geral
O código foi desenvolvido para monitorar o consumo de energia de diferentes aparelhos domésticos, fornecer sugestões para reduzir esse consumo, e analisar a capacidade das fontes de energia renováveis (como solar e eólica) de cobrir esse consumo. Além disso, o sistema gera um relatório com as informações de consumo e sugestões, salvando os dados em um arquivo de texto para acompanhamento posterior.

Listas de Dados de Entrada:

aparelhos: Lista com os nomes dos aparelhos monitorados (Geladeira, Ar Condicionado, etc.).
consumo_diario: Lista com o consumo diário (em kWh) de cada aparelho mencionado na lista aparelhos.
energia_solar: Quantidade de energia gerada diariamente por energia solar (4.0 kWh).
energia_eolica: Quantidade de energia gerada diariamente por energia eólica (2.0 kWh).
Funções Definidas:

consumo_total(consumo): Calcula o total do consumo diário somando os valores de consumo dos aparelhos.
sugestoes_economia(consumo, aparelhos): Analisa o consumo de cada aparelho e gera sugestões de economia para os aparelhos com consumo acima de 1 kWh/dia.
verifica_energia_renovavel(consumo_total, energia_solar, energia_eolica): Compara o consumo total de energia com a energia gerada por fontes renováveis (solar + eólica) e verifica se a energia gerada cobre o consumo.
salvar_dados(consumo_total, sugestoes, analise_renovavel): Salva os resultados do consumo total diário, sugestões de economia e a análise de energia renovável em um arquivo de texto chamado dados_consumo.txt.
    4. Resultado Esperado
    O código gera o seguinte tipo de saída:
    
    perl
    Copiar código
    Consumo total diário: 7.9 kWh
    
    Sugestões para reduzir o consumo de energia:
    - Tente reduzir o uso do Ar Condicionado, pois consome 3.5 kWh diariamente.
    - Tente reduzir o uso do Geladeira, pois consome 1.2 kWh diariamente.
    
    Análise de energia renovável:
    A energia gerada por fontes renováveis cobre o consumo total da casa.
    
    Os dados foram salvos no arquivo 'dados_consumo.txt'.
    Além disso, os dados de consumo, sugestões de economia e a análise de energia renovável são salvos no arquivo dados_consumo.txt.
    
    Conclusão
    Este código oferece uma solução simples e prática para monitorar e otimizar o consumo de energia elétrica em uma residência, com a integração de fontes renováveis. Ele gera sugestões para reduzir o consumo de energia e avalia a eficácia da energia solar e eólica na cobertura desse consumo, ajudando os usuários a economizar e a contribuir para a sustentabilidade.
    
    Instruções para Execução
    Pré-requisitos: Este código foi desenvolvido para rodar em Python 3.x. Certifique-se de ter o Python instalado em seu sistema.
    
    Execução: Para executar o código, basta rodá-lo em um ambiente Python. O arquivo dados_consumo.txt será gerado automaticamente com os resultados.
    
    Customização: Você pode alterar os valores dos aparelhos e o consumo diário para adaptá-los à sua casa ou realizar melhorias no código, como incluir mais fontes de energia renovável ou otimizar a lógica de sugestões.
