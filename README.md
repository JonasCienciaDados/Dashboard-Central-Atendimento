# 📞 Análise de Central de Atendimento — TMA e Volume 2023

Projeto de análise de dados com foco em tempo médio de atendimento (TMA) e volume
de chamadas em uma central de atendimento na área de saúde.

Neste projeto evolui a análise anterior adicionando um **dashboard interativo no Power BI**,
combinando Python para tratamento dos dados e Power BI para visualização executiva.

## 🎯 Objetivo
Identificar padrões de TMA e volume por canal, turno, motivo e agente, gerando
insights acionáveis para gestão de equipes de atendimento.

## 🔍 Perguntas respondidas
- Qual canal tem maior TMA — telefone, chat, e-mail ou WhatsApp?
- Em quais turnos o TMA é maior?
- Quais motivos de contato consomem mais tempo?
- Em qual dia da semana o volume é maior?

## 💡 Principais insights
| Achado | Impacto |
|---|---|
| E-mail tem TMA 2,6x maior que Chat (8.9 vs 3.4 min) | Canal mais custoso da operação |
| Telefone representa 46% do volume total | Principal canal — maior oportunidade de otimização |
| Urgência médica tem o maior TMA (8.0 min) | Necessidade de fila prioritária |
| Turno da noite tem TMA 18% maior que a tarde | Subdimensionamento noturno |
| Sábado é o dia de maior volume (752 atendimentos) | Escala de fim de semana subestimada |

## 📊 Dashboard Power BI
![Dashboard Central de Atendimento](Dashboard%20Central%20Atendimento.png)

## 🛠️ Ferramentas
- **Python** · pandas · Google Colab — tratamento e exportação dos dados
- **Power BI Desktop** — dashboard interativo

## 👤 Sobre
Profissional em transição para Análise de Dados com background em atendimento
ao cliente no setor de saúde. Cursando Ciências de Dados na Estácio.
