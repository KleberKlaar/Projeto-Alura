# Projeto-Alura
# ✨ Gerador Inteligente de Planos de Aula com Gemini AI ✨

> Crie planos de aula completos e personalizados em segundos, otimizados pela inteligência artificial do Google Gemini. Uma ferramenta poderosa para educadores, agora com interface gráfica intuitiva e exportação direta para Word!

## Sobre o Projeto

Este projeto é uma aplicação desktop desenvolvida em Python, utilizando a SDK de Agentes do Google com o modelo Gemini, para automatizar a criação de planos de aula. Ele orquestra uma série de agentes de IA especializados em diferentes etapas do planejamento pedagógico, desde a extração de requisitos até a formatação final, e oferece uma interface gráfica simples para interação, além de uma funcionalidade essencial de exportação para `.docx`.

**Por que usar este Gerador?**

* **Eficiência:** Reduza drasticamente o tempo gasto na criação de planos de aula.
* **Personalização:** Adapte o plano a qualquer tema e nível de ensino (conforme a entrada fornecida).
* **Riqueza de Conteúdo:** Inclui referenciais curriculares (BNCC, LDB, etc.), sugestões de metodologia, materiais e avaliação.
* **Formato Profissional:** Exporte seu plano diretamente para um arquivo Word (.docx) pronto para imprimir e entregar.
* **Tecnologia de Ponta:** Desenvolvido com os avançados modelos de linguagem e SDK de Agentes do Google Gemini.

## Funcionalidades Principais

* Interface Gráfica (GUI) intuitiva construída com `tkinter`.
* Orquestração de múltiplos Agentes de IA para um processo de planejamento detalhado:
    * **Agente Requisitos:** Extrai informações essenciais (tema, nível, duração).
    * **Agente Referenciais Curriculares:** Busca diretrizes e habilidades da BNCC, LDB, etc.
    * **Agente Elaborador:** Rascunha a estrutura base do plano (Título, Objetivos, Conteúdo, Etapas).
    * **Agente Metodologia:** Detalha atividades, métodos de ensino e recursos.
    * **Agente Avaliador:** Sugere formas de avaliação do aprendizado.
    * **Agente Coordenador:** Realiza uma revisão pedagógica (embora seus comentários sejam ignorados na saída final, a etapa contribui para a qualidade do rascunho intermediário).
    * **Agente Final:** Formata o plano completo em um template padrão.
* Integração com Google Search para buscar informações contextuais e referenciais.
* Exportação do plano de aula para um arquivo `.docx` com formatação limpa e apresentável.

## Requisitos

* Python 3.7+
* Bibliotecas Python:
    * `google-generativeai`
    * `google-assistant-sdk` (para o módulo `google.adk`)
    * `python-docx`
    * `tkinter` (geralmente incluído na instalação padrão do Python)
    * `threading`, `os`, `warnings` (módulos padrão do Python)

## Agentes em Ação

Este projeto demonstra o poder da orquestração de Agentes de IA. Cada agente tem um papel específico no pipeline de criação do plano de aula, garantindo que diferentes aspectos (conteúdo, pedagogia, formatação) sejam considerados.

## Autor

Kleber Klaar Ferreira Lima
