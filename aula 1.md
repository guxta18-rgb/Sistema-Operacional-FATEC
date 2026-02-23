#                                                                                                     Resumo 
# Aula 01 - Introdução aos Sistemas Operacionais

Este documento apresenta os principais conceitos discutidos na aula inaugural da disciplina, ministrada pelo **Prof. Me. Deivison S. Takatu** na **FATEC**.

---

## 1. Visão Geral e Metodologia
A disciplina adota uma abordagem prática, incentivando a criação de um **portfólio de projetos** para demonstrar habilidades e facilitar a inserção no mercado de trabalho. A metodologia inclui elementos de **gamificação**, focando em objetivos, habilidades e recompensas para o aprendizado.

## 2. Conceitos Fundamentais de SO
Um Sistema Operacional (SO) é definido como um **software essencial** que atua como o gerente de todos os recursos do computador.

* **Função Principal:** Atuar como a interface entre o usuário e a máquina (hardware).
* **Gerenciamento:** Coordena tanto os componentes físicos (hardware) quanto as aplicações (software).
* **Exemplos Comuns:** Windows, macOS, Linux, Android e iOS.



## 3. Arquitetura e Estrutura Interna
A organização de um SO é hierárquica e modular para garantir eficiência:

* **O Kernel:** É o núcleo do sistema, possuindo acesso direto ao hardware e gerenciando recursos vitais.
* **Modos de Operação:**
    * **Modo Usuário:** Onde operam os programas comuns com privilégios limitados.
    * **Modo Kernel:** Onde o sistema opera com privilégios elevados e acesso total aos recursos.
* **Design de Kernel:** Pode seguir abordagens **Monolíticas** (tudo em um único bloco) ou **Modulares**.

## 4. Gerenciamento de Recursos
Para otimizar o desempenho, o SO realiza tarefas críticas:

* **Escalonamento de Processos:** Define qual processo será executado e por quanto tempo, utilizando algoritmos como **FIFO**, **Round Robin** e **Prioridade**.
* **Memória Principal e Virtual:** Gerencia a alocação dinâmica e a proteção de memória. A **Memória Virtual** permite a expansão lógica da RAM através de técnicas como **paginação** e **segmentação**.
* **Entrada e Saída (E/S):** Gerencia periféricos e organiza o acesso aos dados via **Sistemas de Arquivos**.



## 5. Critérios de Avaliação
A nota final do semestre será composta pela seguinte fórmula:

$$Nota = (P1 \times 0.25) + (P2 \times 0.25) + ((PJ + AT) \times 0.25)$$

* **P1/P2:** Provas Teóricas.
* **PJ:** Projeto.
* **AT:** Atividades semanais.
