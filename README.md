<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

```
# Contexto

Você é um especialista personal trainer e vai me ajudar a montar um treino ideal,
baseado nas cinco variáveis abaixo:

# Área de Variáveis

{{biotipo}} = Ectomorfo
{{periodização}} = 3 dias de treino
{{tipo}} = Funcional e Cardio
{{idade}} = 44
{{sexo}} = Masculino
{{objetivo}} = Ganhar massa
{{tempo}} = 1 hora

# Regras

Regra 1: biotipo
identificar qual o tipo informado nas variaveis acima tipo corporal vai ser algum dos

- Ectomorfo Corpo mais magro, dificil ganhar peso e massa muscular.
- Mesomorfo Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder
- Endomorfo Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Regra 2: periodização
dependendo da quantidade miníma de dias informado na área de variáveis, criar uma das periodização de treino abaixo 
- 1 dia Treino Full Bbdy 
- 3 dias Treino ABC 
- 5 dias Treino ABCDE

Regra 3: tipo
- Funcional Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais
- Maquinário Exercícios feitos em máquinas, com foco em isolar grupos musculares.
- Peso Livre Exercícios com pesos livres, como halteres e barras, para trabalhar varios grupos
musculares simultaneamente.
- Cardio Exercícios voltados para melhorar a resistência cardiovascular, como corrida, bike e caminhada.
- HIIT Treinos intervalados de alta intensidade, ótimos para queima de gordura.

Regra 4: idade
Analisar a idade de cada um para escolher o melhor treino para cada faixa etária.

Regra 5: sexo
Masculino, foco em exercicios com mais pesos e cargas.
Feminino, foco em exercicos com mais queima calórica e dinamismo.

Regra 5: objetivo
Perder peso, criar um treino para maximar a queima de calorias.
Ganhar massa, criar um treino para maximar o ganho de massa e definição do corpo.

Regra 6: tempo
Respeitar o tempo estipulado, lembrando de dar um intervalo de 45 segundos entre cada atividade.

# Resultado esperado
```
Vamos montar um treino ideal para você, levando em consideração todas as variáveis fornecidas. Aqui está um plano de treino funcional e cardio para um ectomorfo de 44 anos, com o objetivo de ganhar massa muscular, em três dias de treino por semana, com sessões de uma hora cada.

### Treino ABC

#### Dia A: Parte Superior do Corpo (Funcional)
1. **Aquecimento**: 10 minutos de corrida leve ou caminhada rápida.
2. **Flexões**: 3 séries de 12 repetições.
3. **Remada Curvada com Halteres**: 3 séries de 12 repetições.
4. **Desenvolvimento de Ombros com Halteres**: 3 séries de 12 repetições.
5. **Supino com Halteres**: 3 séries de 12 repetições.
6. **Prancha**: 3 séries de 45 segundos.
7. **Alongamento**: 5 minutos.

#### Dia B: Parte Inferior do Corpo (Funcional)
1. **Aquecimento**: 10 minutos de corrida leve ou caminhada rápida.
2. **Agachamento Livre**: 3 séries de 15 repetições.
3. **Afundos**: 3 séries de 12 repetições por perna.
4. **Levantamento Terra com Halteres**: 3 séries de 12 repetições.
5. **Elevação de Panturrilhas**: 3 séries de 20 repetições.
6. **Abdominais**: 3 séries de 20 repetições.
7. **Alongamento**: 5 minutos.

#### Dia C: Cardio e Core
1. **Aquecimento**: 10 minutos de corrida leve ou caminhada rápida.
2. **Circuito de Cardio** (3 séries, 1 minuto cada exercício, 30 segundos de descanso entre exercícios):
   - Burpees
   - Polichinelos
   - Mountain Climbers
   - Corrida no Lugar com Joelhos Altos
3. **Prancha Lateral**: 3 séries de 30 segundos por lado.
4. **Bicicleta no Chão**: 3 séries de 20 repetições.
5. **Alongamento**: 5 minutos.

### Dicas Adicionais
- **Nutrição**: Como ectomorfo, é importante consumir uma dieta rica em calorias e proteínas para ajudar no ganho de massa muscular.
- **Descanso**: Certifique-se de ter um bom descanso entre os dias de treino para permitir a recuperação muscular.
- **Hidratação**: Mantenha-se bem hidratado durante todo o dia.
