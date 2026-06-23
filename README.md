# 🚿 AquaSmart — Chuveiro Inteligente

Projeto escolar: demonstração de um chuveiro inteligente gamificado para economia de água.

## 🌊 Funcionalidades

- **Iniciar banho** — cronômetro real, medindo litros e custo em tempo real
- **⚡ Simular banho** — gera um resultado aleatório na hora (ideal / tolerável / excessivo), perfeito para demonstrar em sala sem esperar minutos
- **↺ Resetar aplicativo** — botão para zerar tudo (banhos, pontos, compras), como se ninguém nunca tivesse usado, para repetir a demonstração quantas vezes quiser
- **Luz verde / amarela / vermelha** de feedback de economia
- **Chuveiro animado** com gotas caindo durante o banho
- **Perfis de família** — cada membro tem histórico e pontuação próprios
- **Sistema de pontos** baseado na duração do banho
- **Loja de recompensas com benefícios reais** — cada produto comprado dá um bônus no próximo banho (mais economia ou mais pontos)
- **Barra de benefícios ativos** na tela de banho mostrando os bônus do membro
- **Painel de impacto ambiental** — litros economizados, garrafas, dias de água e economia em R$
- **Histórico** com estatísticas
- **Tema escuro** e **PWA** instalável no celular

## 🎯 Regras de pontuação

| Duração | Classificação | Pontos base |
|---|---|---|
| Até 5 minutos | 🟢 Econômico | +100 pts |
| 5 a 8 minutos | 🟡 Tolerável | +40 pts |
| Acima de 8 minutos | 🔴 Excessivo | +5 pts |

Vazão: 9 L/min · Custo: R$ 0,018 por litro

## 🛍️ Loja e benefícios

Os pontos ganhos com banhos econômicos podem ser trocados por produtos. Cada produto dá um benefício real que se aplica nos próximos banhos:

| Produto | Preço | Benefício |
|---|---|---|
| 🧴 Shampoo Premium | 150 ⭐ | +20% de pontos por banho |
| 💆 Condicionador Premium | 200 ⭐ | +15% de pontos por banho |
| 🫧 Sabonete Artesanal | 120 ⭐ | +10% de pontos por banho |
| 🧖 Toalha Microfibra | 250 ⭐ | +5% de pontos por banho |
| 🛁 Sal de Banho | 180 ⭐ | +25 pontos fixos por banho |
| 🚿 Redutor de Vazão | 350 ⭐ | -30% de consumo de água |
| 🪒 Kit Barbearia | 300 ⭐ | -15% de consumo de água |
| 🧽 Esponja de Banho | 80 ⭐ | -10% de consumo de água |

Os benefícios se acumulam: quem compra vários produtos de água economiza ainda mais (com teto de 60%).

## 📊 Aba Consumo (simulação do mês)

Para medir o consumo diário e mensal da família sem esperar um mês de verdade, existe o botão **📅 Simular mês da família**. A cada toque ele gera um mês inteiro de banhos (os números variam):

- Total de água gasta no mês e total economizado
- Número de banhos e média de litros por dia
- Consumo de cada pessoa (litros no mês, média diária, banhos e quanto economizou)
- Um gráfico de barras com o consumo de cada um dos 30 dias

A água economizada nessa simulação é somada automaticamente ao reservatório da aba **Economia**, que pode então ser usada nas ações do dia a dia.

## 💧 Aba Economia (banco de água)

Toda a água economizada nos banhos vai para um "reservatório" da família. Em vez de virar dinheiro, essa água pode ser usada em ações reais do dia a dia que ajudam o meio ambiente:

| Ação | Água usada |
|---|---|
| 🐶 Encher o pote do pet | 1 L |
| 🪴 Regar um vaso de planta | 2 L |
| 🚽 Dar uma descarga | 6 L |
| 🌳 Regar uma árvore | 10 L |
| 🍽️ Lavar a louça do almoço | 20 L |
| 🧺 Lavar roupa à mão | 40 L |
| 🚗 Lavar o carro com balde | 60 L |
| 🌻 Regar uma horta inteira | 100 L |

A ideia é mostrar, de forma concreta, no que aquela economia de água poderia ser aproveitada de verdade.
