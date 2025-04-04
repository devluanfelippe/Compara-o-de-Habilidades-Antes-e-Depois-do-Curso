# Comparação de Habilidades Antes e Depois do Curso

## Descrição

Este projeto consiste em um script Python que gera um gráfico de barras comparando o nível de conhecimento em diferentes habilidades antes e depois da realização de um curso. O objetivo é visualizar de forma clara o progresso e o impacto do curso no desenvolvimento dessas habilidades.

## Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **matplotlib:** Biblioteca para criação de gráficos e visualizações de dados.

## Como Executar

1.  **Certifique-se de ter o Python instalado em seu sistema.**
2.  **Instale a biblioteca matplotlib:**
    ```bash
    pip install matplotlib
    ```
3.  **Salve o código Python fornecido em um arquivo (por exemplo, `comparacao_habilidades.py`).**
4.  **Execute o script a partir do seu terminal:**
    ```bash
    python comparacao_habilidades.py
    ```

   Ao executar o script, uma janela com o gráfico de barras será exibida, mostrando a comparação do nível de conhecimento nas habilidades "Android", "Java" e "Desenvolvimento de Apps" antes e depois do curso.

## Dados

Os dados utilizados para gerar o gráfico são definidos diretamente no script:

* `skills`: Uma lista contendo os nomes das habilidades ('Android', 'Java', 'Desenvolvimento de Apps').
* `before_course`: Uma lista numérica representando o nível de conhecimento em cada habilidade antes do curso (em uma escala de 0 a 5).
* `after_course`: Uma lista numérica representando o nível de conhecimento em cada habilidade depois do curso (na mesma escala).

Estes dados podem ser facilmente modificados no script para refletir diferentes habilidades e níveis de conhecimento.

## Visualização

O script gera um gráfico de barras agrupadas, onde cada grupo representa uma habilidade. Dentro de cada grupo, há duas barras: uma representando o nível de conhecimento "Antes" do curso (em cor `lightcoral`) e outra representando o nível de conhecimento "Depois" do curso (em cor `lightskyblue`).

O gráfico inclui:

* Um título claro: "Comparação de Habilidades Antes e Depois do Curso".
* Rótulos para os eixos X (Habilidades) e Y (Nível de Conhecimento (0 a 5)).
* Marcadores no eixo X correspondentes a cada habilidade.
* Uma legenda para distinguir as barras "Antes" e "Depois".
* Uma grade horizontal para facilitar a leitura dos níveis de conhecimento.
* O eixo Y é limitado de 0 a 5 para corresponder à escala de conhecimento.

## Possíveis Melhorias

* **Flexibilidade dos Dados:** Ler os dados de um arquivo externo (CSV, Excel) em vez de defini-los diretamente no script.
* **Mais Habilidades:** Adicionar suporte para um número variável de habilidades.
* **Personalização:** Permitir que o usuário configure cores, títulos e outros aspectos do gráfico.
* **Análise Estatística:** Adicionar alguma forma de análise estatística para quantificar a significância da melhora.
* **Salvar o Gráfico:** Implementar a funcionalidade para salvar o gráfico gerado em diferentes formatos de imagem (PNG, JPG, PDF).
