# 🧠 Análise de Hábitos dos Alunos e seu Impacto no Desempenho Escolar

Este projeto tem como objetivo analisar dados relacionados aos **hábitos diários de estudantes** e entender como esses fatores influenciam o **desempenho em exames escolares**. Utilizamos técnicas de ciência de dados e machine learning com a biblioteca **PySpark**, ideal para manipular grandes volumes de dados de forma distribuída.

## 🎯 Objetivo

Prever o desempenho dos alunos em exames (`exam_score`) com base em variáveis relacionadas ao estilo de vida, como horas de estudo, uso de redes sociais, sono, alimentação e outros hábitos.

## 📦 Fonte dos Dados

O conjunto de dados foi obtido a partir do [Kaggle](https://www.kaggle.com/) e contém **1.000 registros de alunos**, com informações sobre:

- Estilo de vida (estudo, sono, exercícios)
- Fatores sociais (emprego, atividades extracurriculares)
- Condições de infraestrutura (internet, presença)
- Saúde mental
- Resultado final: nota no exame

## 📑 Dicionário de Variáveis

| Variável                          | Descrição                                                         |
|----------------------------------|-------------------------------------------------------------------|
| `student_id`                     | Identificador único do aluno (não usado na predição)             |
| `age`                            | Idade do aluno                                                    |
| `gender`                         | Gênero do aluno (`Male`, `Female`)                                |
| `study_hours_per_day`           | Horas de estudo por dia                                           |
| `social_media_hours`            | Horas gastas em redes sociais por dia                             |
| `netflix_hours`                 | Horas assistindo streaming por dia                                |
| `part_time_job`                 | Possui emprego de meio período? (`Yes`/`No`)                      |
| `attendance_percentage`         | Porcentagem de presença nas aulas                                 |
| `sleep_hours`                   | Horas de sono por dia                                             |
| `diet_quality`                  | Qualidade da alimentação (`Poor`, `Average`, `Good`)              |
| `exercise_frequency`            | Frequência de exercícios por semana                               |
| `parental_education_level`      | Nível de escolaridade dos pais (`None`, `High School`, `Bachelor`)|
| `internet_quality`              | Qualidade da internet (`Poor`, `Average`, `Good`)                 |
| `mental_health_rating`          | Avaliação de saúde mental (1 a 10)                                |
| `extracurricular_participation` | Participa de atividades extracurriculares? (`Yes`/`No`)          |
| `exam_score`                    | Nota final obtida no exame (variável-alvo)                        |

## 🛠 Tecnologias e Ferramentas

- 🐍 Python
- ⚡ PySpark
- 📊 Jupyter Notebook
- 🧪 Pandas (para análises complementares)
- 📁 Dataset CSV

## 🚀 Etapas do Projeto

1. **Exploração e Limpeza dos Dados**
2. **Análise Estatística e Visual**
3. **Preparação dos Dados**
4. **Criação de Modelos Preditivos**
5. **Avaliação e Interpretação dos Resultados**

## 🧑‍💻 Autor

**Diego Kazadi**  
Mestrando em Ciência da Computação pela Universidade Federal de Campina Grande (UFCG)

