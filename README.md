# Space_connect_PromptAI

# Projeto Aurora - Mission Control AI

**Integrantes:**
1 - Nicolas Andrade Rodrigues — RM: 572782
2 - Lucas Caram Bueno  — RM: 570158

Este projeto consiste em um sistema inteligente de monitoramento de missões espaciais que integra automação de sensores, regras lógicas de tomada de decisão e inteligência artificial local para gerenciar cápsulas adaptativas e plantas-sensoras.

## O que é o Projeto Aurora?

O Projeto Aurora nasceu da convergência de dois conceitos fundamentais voltados para a exploração espacial e a preservação da vida:

1. **Plantas-Sensoras como Precursoras:** Envio de vegetação ao espaço antes de missões tripuladas humanas. Como as plantas reagem ativamente a variações ambientais, como radiação, escassez hídrica e flutuações térmicas, o uso de sensores e inteligência artificial permite interpretar essas respostas biológicas e mapear as condições locais em detalhes de antemão.
2. **Cápsulas Biométricas Adaptativas:** Desenvolvimento de ambientes que se ajustam ao estado psicológico e físico do tripulante. Monitorando sinais vitais como batimentos cardíacos e temperatura corporal, o sistema identifica quadros de estresse ou ansiedade e altera dinamicamente variáveis como iluminação, som ambiente e temperatura para restabelecer o bem-estar do astronauta.

Na união dessas ideias, as cápsulas preatoras coletam dados e aprendem autonomamente quais são os parâmetros ideais para a sobrevivência e a eficiência de uma futura tripulação humana no corpo celeste de destino.

## O que o Sistema Faz?

O software desenvolvido atua como o painel de Controle de Missão (Mission Control) da cápsula, simulando a telemetria e gerenciando a inteligência interna do módulo por meio dos seguintes passos:

* **Simulação de Telemetria:** Gera dados dinâmicos em tempo real sobre o estado do módulo (temperatura interna, nível de bateria, eficiência da geração solar, taxa de radiação, umidade ambiente), saúde do astronauta (frequência cardíaca em BPM) e status biológico das plantas.
* **Sistema Automático de Alertas:** Compara continuamente cada indicador coletado com limites de segurança preestabelecidos, categorizando o status geral da missão em níveis: Normal, Atenção ou Crítico.
* **Mecanismo de Resposta Dinâmica:** Executa contramedidas imediatas e automáticas baseadas em regras de engenharia espacial, como ativação de sistemas de resfriamento, isolamento de radiação, acionamento de protocolos de redundância em comunicações e ajustes ambientais em resposta ao estresse biométrico.
* **Análise por Inteligência Artificial:** Integra o modelo de linguagem local Llama 3.2 (via Ollama) para ler o cenário de alertas e formular diagnósticos contextuais concisos e recomendações prioritárias para as equipes de comando ou para os sistemas de bordo.
* **Monitoramento Contínuo:** Executa rotinas cíclicas de varredura que atualizam o console de controle de forma limpa, permitindo observar a estabilização ou a degradação do ecossistema da cápsula ao longo do tempo.

## Demonstração

![Dados da missão] <img width="491" height="432" alt="image" src="https://github.com/user-attachments/assets/d3c462b6-8145-4f18-9177-ec397b5593ad" />

![Alerta crítico] <img width="502" height="601" alt="image" src="https://github.com/user-attachments/assets/7c0601a4-c34f-4b13-8e59-fc67b728dc36" />

