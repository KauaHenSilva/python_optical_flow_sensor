# python_optical_flow_sensor

Este repositório contém dois Jupyter Notebooks que demonstram métodos de fluxo óptico utilizando a biblioteca OpenCV. São apresentadas duas abordagens distintas: o método de fluxo óptico denso de Farneback e o método de fluxo óptico esparso de Lucas-Kanade. Ambos os notebooks são otimizados para execução no **Google Colab**, permitindo testar e visualizar os resultados diretamente na nuvem.

---

## Notebooks

### `optical_flow_dense.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_optical_flow_sensor/blob/main/optical_flow_dense.ipynb)

**Funcionalidade:** Rastreamento de movimento utilizando o método de fluxo óptico denso de Farneback.

Este notebook implementa o cálculo do fluxo óptico denso para rastrear o movimento em vídeos.

#### Principais Funcionalidades:
- Uso do método de Farneback para cálculo do fluxo óptico denso.
- Suporte para vídeos armazenados no Google Drive.
- Rastreamento preciso de movimento em cada quadro do vídeo.
- Exibição dos resultados diretamente no notebook.

---

### `optical_flow_sparce.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_optical_flow_sensor/blob/main/optical_flow_sparce.ipynb)

**Funcionalidade:** Rastreamento de movimento utilizando o método de fluxo óptico esparso de Lucas-Kanade.

Este notebook usa a técnica de Lucas-Kanade para calcular o fluxo óptico esparso em vídeos.

#### Principais Funcionalidades:
- Uso do método de Lucas-Kanade para cálculo do fluxo óptico esparso.
- Suporte para vídeos armazenados no Google Drive.
- Rastreamento eficiente de pontos de interesse em cada quadro do vídeo.
- Exibição dos resultados diretamente no notebook.

---

## Como Usar no Google Colab

Para executar os notebooks no Google Colab, siga os passos abaixo:

1. **Acesse o Google Colab:**
  - Abra o [Google Colab](https://colab.research.google.com/).

2. **Carregue os Notebooks:**
  - Clique em `Arquivo` > `Abrir notebook`.
  - Escolha a aba `GitHub` e insira o link deste repositório.
  - Selecione o notebook desejado (`optical_flow_dense.ipynb` ou `optical_flow_sparce.ipynb`).

3. **Conecte ao Google Drive (se necessário):**
  - Alguns notebooks exigem acesso ao Google Drive para carregar vídeos.

4. **Execute as Células:**
  - Conecte-se ao ambiente clicando em `Conectar` no canto superior direito.
  - Execute as células sequencialmente para processar o vídeo e visualizar os resultados.

5. **Teste com seus Próprios Vídeos (Opcional):**
  - Faça o upload de um vídeo diretamente no Google Colab usando:
    ```python
    from google.colab import files
    uploaded = files.upload()
    ```
  - Substitua o caminho do vídeo no notebook pelo arquivo enviado.

---
