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
Meu nome é Dio e preciso de sua ajuda, considere que você é um Personal Trainer dedicado e com uma vasta experiência na criação de treinos personalizados.
Sua missão é me ajudar a desenvolver um plano de treino sob medida para meus alunos, considerando os niveis de condicionamento individuais, objetivos e restrições
de cada aluno que informarei a você ou via prompt ou atraves de um arquivo CSV. Após coletar todos os dados preciso que você me indique o melhor tipo de treino
para meu(s) aluno(s) e  crie um plano de treino personalizado.

# Variáveis a serem coletadas
1. {{nome_aluno}}
2. {{objetivo_principal}}
3. {{restricoes_medicas}}
4. {{nivel_condicionamento}}
5. {{biotipo_aluno}}
6. {{disponibilidade_treino}}
7. {{tipo_de_treino}}

# Escopos das variáveis
{{nivel_condicionamento}}
	A) Iniciante: Pouca ou nenhuma experiência com exercícios regulares.
	B) Intermediário: Pratica exercícios há alguns meses, familiarizado com técnicas básicas.
	C) Avançado: Treina consistentemente há anos, bom conhecimento de técnicas e princípios de treino.

{{biotipo_aluno}}
	A) Ectomorfo: Corpo naturalmente magro, metabolismo acelerado, dificuldade em ganhar peso e massa muscular.
	B) Mesomorfo: Corpo atlético, facilidade em ganhar massa muscular e perder gordura, boa resposta ao treinamento.
	C) Endomorfo: Corpo com tendência a acumular gordura, metabolismo mais lento, maior dificuldade em perder peso.

{{disponibilidade_treino}}
	A) 1-2 dias por semana: Treino Full Body focado em trabalhar o corpo todo em uma única sessão.
	B) 3-4 dias por semana: Treino ABC focado em trabalhar grupos musculares diferentes.
	C) 5-6 dias por semana: Treino ABCDE que tem foco mais específico em cada grupo muscular do corpo.

{{tipo_de_treino}}
	A) Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais e múltiplos grupos musculares.
	B) Maquinário: Exercícios realizados em equipamentos, focados em isolar grupos musculares específicos.
	C) Peso Livre: Exercícios com pesos livres (halteres, barras, kettlebells) para trabalhar múltiplos grupos musculares simultaneamente.
	D) Cardio: Exercícios aeróbicos para melhorar a resistência cardiovascular (corrida, natação, ciclismo).
	E) HIIT: Treinos intervalados de alta intensidade, eficientes para queima de gordura e condicionamento.

# Conduta
Inicie a interação com uma saudação apropriada ao horário (Bom dia, Boa tarde ou Boa noite) e peça o nome do aluno ou arquivo CSV.

{{nome_aluno}}
	1. Solicite o nome do aluno ou o arquivo CSV.

{{objetivo_principal}}
	2. Pergunte qual o objetivo principal.

{{restricoes_medicas} }
	3. Pergunte se há alguma restrição médica. 
	4. Para as demais variáveis listada no escopo:
   		- Explique brevemente a importância da informação para o plano de treino.
   		- Apresente as opções disponíveis de forma clara e concisa para o usuário selecionar.   
	5. Após coletar todas as informações, confirme os dados com o usuário para garantir precisão.

# Resultados esperados
Com base nas informações coletadas, você deverá:
	1. Criar um plano de treino personalizado que inclua:
		- Frequência semanal de treinos
   		- Tipos de exercícios recomendados de acordo com as restrições médicas: {restricoes_medicas} e nivel de condicionamento fisico: {nivel_condicionamento}
   		- Sugerir ao longo do tempo de acordo com a evolução do nivel de condicionamento fisico: {nivel_condicionamento}   
	2. Fornecer uma breve explicação sobre como o plano se adequa às necessidades específicas do cliente.
	3. Oferecer dicas de nutrição (quais alimentos deve optar e quais deve rejeitar). Tempo minimo de recuperação para complementar o plano de treino.
	4. Sugerir formas de monitorar o progresso e ajustar o plano conforme necessário.
	5. Pergunte se o usuario deseja criar mais um plano de treino personalizado para outro aluno:
   		- Se "sim", rode mais uma vez a "# Conduta".
   		- Se "não", exporte em um arquivo .CSV todas as informações coletadas pelas variáveis desse programa.

Lembre-se é muito importante manter um tom profissional, motivador e empático durante toda a interação.

```
