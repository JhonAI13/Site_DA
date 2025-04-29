# Site_DA: Simulação de Lançamento de Moeda com Streamlit

Este projeto demonstra uma aplicação web interativa criada com Streamlit para simular o lançamento de uma moeda e visualizar a convergência da frequência observada para a probabilidade teórica (Lei dos Grandes Números).

## Qual o objetivo dele?

O objetivo principal desta aplicação é:

1.  **Simular:** Realizar um número configurável de lançamentos de uma moeda justa (probabilidade de 0.5 para cada lado).
2.  **Visualizar:** Mostrar graficamente, em tempo real, como a proporção de "caras" (representada pelo valor 1 na simulação) evolui a cada lançamento.
3.  **Demonstrar:** Ilustrar de forma interativa a Lei dos Grandes Números, onde a média das amostras (proporção de caras) tende a se aproximar da probabilidade esperada (0.5) conforme o número de tentativas aumenta.

## Como usar?
Para executar esta aplicação localmente, siga os passos:

1.  **Pré-requisitos:** Certifique-se de ter Python 3.x instalado em seu sistema.
2.  **Clonar/Baixar:** Obtenha os arquivos do projeto (se estiver em um repositório Git, clone-o; caso contrário, baixe os arquivos `app.py` e `requirements.txt` para um diretório).
3.  **Navegar até o Diretório:** Abra seu terminal ou prompt de comando e navegue até o diretório onde você salvou os arquivos (o diretório `Site_DA`).
4.  **Instalar Dependências:** Execute o comando abaixo para instalar as bibliotecas necessárias listadas no arquivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```
5.  **Executar a Aplicação:** Inicie a aplicação Streamlit com o comando:
    ```bash
    streamlit run app.py
    ```
6.  **Interagir:** O Streamlit deverá abrir automaticamente uma nova aba no seu navegador web padrão.
    *   Use o controle deslizante (`slider`) para escolher o número de lançamentos (tentativas) que deseja simular.
    *   Clique no botão "Executar".
    *   Observe o gráfico de linha sendo atualizado dinamicamente, mostrando a proporção de "caras" após cada lançamento simulado.

## Quais tecnologias usei?

As principais tecnologias e bibliotecas utilizadas neste projeto são:

*   **Python:** Linguagem de programação base.
*   **Streamlit:** Framework para criação rápida de aplicações web interativas para ciência de dados e visualização.
*   **SciPy:** Biblioteca científica para Python, utilizada aqui especificamente para gerar números aleatórios seguindo uma distribuição de Bernoulli (`scipy.stats.bernoulli`), que modela perfeitamente o lançamento de uma moeda.
*   **Pandas:** Embora listado no `requirements.txt`, não foi diretamente utilizado no script `app.py` fornecido. É uma biblioteca fundamental para manipulação e análise de dados em Python.

## Quais competências eu consegui?

Ao desenvolver este projeto, você demonstrou e/ou aprimorou as seguintes competências:

*   **Desenvolvimento Web Interativo:** Criação de interfaces de usuário web simples e interativas usando Streamlit.
*   **Visualização de Dados:** Utilização de gráficos (neste caso, `st.line_chart`) para apresentar dados de forma dinâmica e compreensível.
*   **Simulação Estatística:** Aplicação de conceitos de probabilidade (Distribuição de Bernoulli) e simulação de eventos aleatórios usando SciPy.
*   **Compreensão da Lei dos Grandes Números:** Demonstração prática de um conceito estatístico fundamental.
*   **Programação em Python:** Uso de funções, loops, condicionais e manipulação de dados básicos.
*   **Gerenciamento de Dependências:** Utilização de `requirements.txt` para definir e instalar as bibliotecas necessárias para o projeto.