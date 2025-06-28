# 🍇 Classificador de Frutas com IA

## 🎯 Objetivo do Projeto

Desenvolver um classificador de frutas utilizando aprendizado de máquina supervisionado. O modelo é capaz de identificar imagens de maçã, banana, uva e limão com base em um dataset personalizado.

---

## 🧰 Tecnologias Utilizadas

- Python (Google Colab)
- Biblioteca FastAI
- Pillow (PIL) e Scikit-Image
- Google Drive (armazenamento do dataset)

---

## ⚙️ Descrição do Funcionamento

1. O código se conecta ao Google Drive onde está armazenado o dataset de imagens.
2. As imagens são organizadas em pastas por rótulo (maca, banana, uva, limao).
3. O modelo usa a arquitetura `resnet18` pré-treinada e é ajustado ao dataset.
4. Após o treinamento, é possível carregar uma imagem nova e o modelo prevê qual fruta é exibida.
5. A interface interativa permite o envio de imagens diretamente no notebook.

---

## ▶️ Como Executar/Testar o Projeto

1. Acesse o [notebook no Google Colab](link_colab_aqui).
2. Monte seu Google Drive com o botão “Connect to Drive”.
3. Garanta que o dataset de imagens esteja no caminho:  
   `/content/drive/MyDrive/frutas_dataset`
4. Execute todas as células do notebook.
5. Use a interface de upload para testar com imagens de frutas.

---

## 📊 Resultados Obtidos

- O modelo foi treinado com aproximadamente 80 imagens (20  imagens em média por fruta).
- Acurácia final obtida: (ex: **92%**) com baixa taxa de erro.
- Exemplo de teste:
  
![Exemplo](exemplos_imagens/exemplo_maca.png)

---

## 📁 Dataset

O dataset usado está disponível no Google Drive e pode ser acessado pelo link:  
🔗 [Link para o Dataset](https://drive.google.com/drive/folders/1W7v7RozsY9phklFZsEwOlwbteX0j7sWB?usp=drive_link)

---


## 👨‍💻 Autores

Kayque Soares, Henrique Murakami, Leonardo Gonçalves e Luis Fernando

