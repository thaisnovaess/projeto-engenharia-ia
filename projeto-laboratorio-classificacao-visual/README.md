SM2 - Laboratório de Classificação Visual 

⚖️ Laboratório de Classificação Visual e Ética em IA Este repositório documenta a segunda parte da atividade prática de Engenharia de Instrução, focada na identificação de vieses algorítmicos através do treinamento de modelos de visão computacional.

🔍 Parte 1: Experimento Técnico (Teachable Machine) O objetivo foi criar deliberadamente um modelo de classificação enviesado para observar como a falha nos dados de treinamento corrompe o resultado final.

Categorias: "Perfil Liderança" vs. "Perfil Operacional".

Dataset Enviesado: Foram utilizadas 20 imagens por categoria com critérios estereotipados (ex: homens de terno para liderança e roupas informais para operacional).

Modelo Gerado: Acesse o modelo aqui.

Resultado: O modelo apresentou falhas de classificação (falsos positivos/negativos) ao ser testado com indivíduos que não correspondiam aos estereótipos iniciais.

📝 Parte 2: Memorial de Impacto e Ética Análise reflexiva sobre a relação entre dados técnicos e impacto humano, utilizando verbos no presente do indicativo.

⚙️ Mecanismo do Viés O viés acontece quando o algoritmo aprende padrões restritos que não representam a realidade. O sistema decide com base exclusiva no que vê no treinamento; logo, se os dados são limitados, o algoritmo gera uma visão distorcida e erra ao classificar exemplos diversos.

👤 Consequência Social Um sistema enviesado causa problemas reais, como a perda de oportunidades de emprego para candidatos plenamente capazes. Esse erro gera frustração e uma profunda sensação de injustiça, pois o sistema marginaliza perfis que não se encaixam em seu padrão automatizado, afetando diretamente a vida e a dignidade das pessoas.

🛡️ Ação Mitigadora (Human-in-the-loop) A intervenção humana garante a equidade através da curadoria ativa. Especialistas analisam os dados antes do treinamento para identificar lacunas de representatividade e ajustar as categorias. Mesmo após a implementação, pessoas acompanham os resultados e corrigem falhas, o que torna o sistema mais justo e confiável.

🛠️ Tecnologias Utilizadas Ferramenta de Treinamento: Teachable Machine (Google).

Conceito Aplicado: Human-in-the-loop e Mitigação de Viés.

Data de Execução: Maio de 2026.
