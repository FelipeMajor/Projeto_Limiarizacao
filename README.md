# 📊 Equalização de Histograma em Imagens Digitais

Projeto desenvolvido para a disciplina de Processamento Digital de Imagens com o objetivo de implementar, analisar e comparar a técnica de **equalização de histograma** em imagens em tons de cinza e em imagens coloridas.

---



## 📌 Sobre o Projeto

A equalização de histograma é uma técnica utilizada para melhorar o contraste de imagens, redistribuindo os níveis de intensidade dos pixels de forma mais uniforme. Essa técnica é especialmente útil em imagens com:

- Baixo contraste  
- Iluminação inadequada  
- Detalhes pouco visíveis  

Neste projeto, foi desenvolvido um notebook em Python que realiza todo o processo de:

- Leitura de imagem da Internet  
- Conversão para tons de cinza  
- Cálculo e exibição do histograma  
- Aplicação da equalização  
- Comparação visual e estatística dos resultados  

Além disso, foi realizado um segundo experimento aplicando a equalização **separadamente nos canais RGB de imagens coloridas**.

---

## 🎯 Objetivos da Atividade

O projeto atende aos seguintes requisitos:

✔ Desenvolver um programa para leitura de imagem via URL  
✔ Converter a imagem para tons de cinza  
✔ Calcular o histograma da imagem  
✔ Aplicar equalização de histograma  
✔ Exibir imagens de todas as etapas do processo  
✔ Exibir histogramas antes e depois da equalização  
✔ Incluir análises textuais explicando cada etapa  
✔ Realizar experimento adicional com equalização nos canais RGB  
✔ Comparar resultados com e sem equalização  

---

## 🧪 Experimentos Realizados

### 🔹 1. Equalização em Tons de Cinza

Etapas realizadas:

1. Leitura da imagem da Internet  
2. Conversão para escala de cinza  
3. Cálculo do histograma original  
4. Aplicação da equalização  
5. Exibição da imagem equalizada  
6. Comparação dos histogramas antes e depois  

**Análise realizada:**
- Observação da redistribuição dos níveis de intensidade  
- Avaliação do ganho de contraste  
- Comparação visual da melhoria dos detalhes  

---

### 🔹 2. Equalização em Imagens Coloridas (RGB)

Neste experimento:

- A imagem **não foi convertida para cinza**
- Os canais **R, G e B** foram separados
- A equalização foi aplicada individualmente em cada canal
- Os canais foram recombinados para gerar a imagem final

Foram utilizados três exemplos diferentes (pessoas e objetos coloridos).

**Análise realizada:**
- Comparação da imagem colorida original e equalizada  
- Comparação dos histogramas por canal  
- Observação de possíveis alterações de cor  
- Discussão sobre vantagens e limitações do método  

---

## 🛠️ Tecnologias Utilizadas

- Python 3  
- Jupyter Notebook  
- NumPy  
- Matplotlib  
- OpenCV (cv2)  
- Requests  

---

## 📂 Estrutura do Repositório

```
📁 projeto-equalizacao-histograma
├── main.ipynb
├── README.md
```

- `main.ipynb` → Notebook com todo o desenvolvimento, imagens, gráficos e análises textuais.  
- `README.md` → Documentação do projeto.  

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```
git clone https://github.com/FelipeMajor/Projeto_Limiarizacao.git
```

2. Instale as dependências:

```
pip install numpy matplotlib opencv-python requests
```

3. Abra o notebook:

```
jupyter notebook main.ipynb
```

---

## 📈 Resultados Observados

Durante os experimentos foi possível observar que:

- A equalização melhora significativamente o contraste em imagens de baixa qualidade.  
- O histograma torna-se mais distribuído ao longo do intervalo de intensidade.  
- Em imagens coloridas, a equalização por canal pode alterar levemente a percepção das cores.  
- Nem sempre a equalização produz um resultado visualmente mais agradável — dependendo da imagem, pode gerar exagero de contraste.  

---

## 📌 Conclusão

O projeto permitiu compreender tanto o funcionamento matemático quanto o impacto visual da equalização de histograma.  

Além da implementação prática, a análise comparativa dos histogramas e das imagens resultantes reforçou a importância de interpretar os resultados antes de aplicar a técnica em contextos reais.  

A atividade demonstrou que a equalização é uma ferramenta poderosa, mas deve ser aplicada com critério, especialmente em imagens coloridas.

---

## 👩‍💻 Desenvolvedores

Fabricio da Costa Fernandes
<br>Felipe de Lima Major
<br>Lilian Gimenez Teixeira

**Universidade Federal do ABC (UFABC), Santo André, SP**
<br>Disciplina: Processamento Digital de Imagens