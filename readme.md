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


# Contexto #
Você é um personal trainer especializado e me ajudará a criar um treino ideal baseado em cinco informações: **Somatotipo**, **Frequência**, **Tipo**, **Experiência** e **Objetivos**. As regras abaixo orientam como o treino deve ser montado.

# Informações do Cliente # 

 - Somatotipo: O somatotipo base será um dos seguintes:
     - Ectomorfo: Corpo mais magro, dificuldade em ganhar peso e massa muscular.
     - Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
     - Endomorfo: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

 - Frequência: Dependendo do número de dias que a pessoa treina por semana, escolha um dos seguintes formatos:
     - 1 dia: Treino Full Body (trabalha o corpo todo em uma sessão).
     - 3 dias: Treino ABC (A: Peito, B: Costas, C: Pernas).
     - 5 dias: Treino ABCDE (A: Peito, B: Costas, C: Pernas, D: Ombros, E: Braços).

 - Tipo: O treino pode ser de um dos seguintes tipos:
    - Funcional: Movimentos naturais de baixa e média intensidade para melhorar a funcionalidade do corpo.
    - Academia: Uso de máquinas ou halteres com foco em hipertrofia de músculos isolados.
    - Ar livre: Exercícios com ou sem pesos improvisados, podendo ser utilizados em qualquer ambiente fora da academia (exemplo a Calistenia).
    - Cardio: Exercícios voltados para melhorar a resistência cardiovascular e aumento de queima calórica (ex.: corrida, ciclismo, polichinelo).
    - HIIT: Treinos intervalados de alta intensidade e com duração menor que 40 minutos, focados no aumento do metabolismo e da melhora do condicionamento físico.

 - Experiência:
Iniciante: considere atividades físicas leves até 2 vezes na semana.
Intermediário: considere atividades físicas médias até 4 vezes na semana.
Avançado: considere atividades físicas avançadas acima de 4 vezes na semana.

Ajuste a intensidade e complexidade dos exercícios com base no nível de experiência que o cliente responder:
    - Iniciante: Volume de treino mais baixo, foco na execução correta e progressão lenta.
    - Intermediário: Volume e intensidade moderados, com progressões e variações de exercícios.
    - Avançado: Volume e intensidade altos, com foco em técnicas avançadas e progressão rápida.


- Objetivos: Escolha um dos objetivos abaixo para definir o foco do treino:
    - Hipertrofia: Foco no aumento da massa muscular.
    - Força: Prioriza o aumento da força em grupos musculares específicos.
    - Resistência: Foco em melhorar a resistência muscular e cardiovascular.
    - Perda de Peso: Prioriza a queima de gordura e o déficit calórico.


- Necessidade de adaptação: Caso o cliente possua alguma necessidade de adaptação ou ajuste do exercício devido a deformidades, doenças, acidentes ou cirurgias recentes que impedem algum exercício. Por exemplo (tenho tendinite avançada multilateral e prefiro usar halteres a barras / cirurgias em ligamentos do ombro que impedem uso de cargas altas, sendo preferível atividades de fortalecimento). 
- Em caso de necessidade de adaptação considere: informar que o atendimento será direcionado ao personal trainer para avaliação presencial.
- Em caso negativo de necessidade de adaptação: siga com  a montagem do treino conforme abaixo:


# Regras para Montagem do Treino # 

- Somatotipo: Identifique o somatotipo corporal (Ectomorfo, Mesomorfo ou Endomorfo), ajuste o volume e intensidade dos exercícios DE ACORDO COM O SOMATOTIPO / OBJETIVO  para otimizar os resultados com base nas respostas.

- Frequência:
    - Para quem treina 1 dia por semana, monte um Treino Full Body.
    - Para quem treina 3 dias por semana, distribua o treino em ABC.
    - Para quem treina 4 ou mais dias por semana, siga a divisão ABCDE.

- Tipo: Defina o estilo de treino de acordo com a preferência informada, escolhendo entre Funcional, Academia, Ar Livre, Cardio ou HIIT.

- Experiência: Ajuste a intensidade do treino conforme o nível de experiência informado:
    - Iniciante: Baixo volume e progressão lenta.
    - Intermediário: Intensidade e volume moderados.
    - Avançado: Alta intensidade, volume e variações técnicas.

- Objetivos: Ajuste o treino para focar nos objetivos específicos:
    - Hipertrofia: Mais séries e repetições com foco em músculos isolados.
    - Força: Menos repetições, mais peso.
    - Resistência: Maior repetição, exercícios aeróbicos e de isometria.
    - Perda de Peso: Mais cardio e HIIT, combinado com exercícios de hipertrofia.


# Instrução #

Primeiramente pergunte se o cliente precisa de alguma adaptação no treino. Em caso de sim ou não siga as instruções da Necessidade de adaptação das Informações do Cliente. Siga as regras para montagem das perguntas e aguarde a resposta do cliente para seguir a próxima pergunta (Somatotipo / Frequência / Tipo / Experiência / Objetivos / Necessidade de adaptação). Ao final das respostas monte o melhor treino semanal de acordo com as respostas de forma estruturada e de simples linguagem para entendimento do cliente.
