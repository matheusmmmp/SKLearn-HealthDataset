<h1 align="center">
   🦠<a href="#"> Modelos de Classificação de Câncer </a>
</h1>

<h3 align="center">
   Tratamento de Dados de Alta Dimensionalidade e Modelagem de Classificadores de Câncer
</h3>

<h4 align="center"> 
	 Status: Concluído🚀
</h4>
 
<p align="center">
 <a href="#sobre-o-projeto">Sobre</a> •
 <a href="#funcionalidades">Funcionalidades</a> •
 <a href="#conclusão">Conclusão</a> •
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#licença">Licença</a>
</p>


## ✎Sobre o projeto

Este notebook é uma forma de praticar meus conhecimentos em ciência de dados, principalmente com a **redução de dimensionalidade da biblioteca SKLearn**. Ele nos orienta em um fluxo de trabalho para resolver um problema em um cenário de classificação de um câncer através de 33 dados, onde através de algoritmos árvore de decisão e redução de dimensionalidade, será possivel reduzir o número de parametros presentes nos modelos sem afetar sua precisão.

Será estudado metodos automatizados para a seleção de features, tais como: SelectKBest e o RFE. E também será realizado uma análise dos dados e selecionado a remoção de features que não apresentem um impacto na precisão do modelo. Por fim, os modelos serão comparados e documentados. Também será utilizado o RFECV (RFE com Cross Validation) para determinar qual o menor número de features necessários para atingirmos o melhor resultado e quais features são necessários para chegar a esse resultado.

Para visualização de dados de alta dimensionalidade em um plano, é necessário realizar transformações, para isso irá ser utilizado os métodos PCA e o t-SNE, permitindo assim uma melhoraram para a apresentação de tais dados.
  
O principal objetivo deste notebook é servir como um guia de fluxo de trabalho passo a passo, permitindo que eu mesmo revise este caderno e sirva de estudo para casos futuros.

Este notebook foi desenvolvido dentro do ambiente Google Colab.

---

## ⚙Funcionalidades

- [x]  Pré-Processamento;
- [x]  Geração de Modelos de Arvore de Decisão;
- [x]  Visualização de Dados;

---

## 🔬Conclusão

Dentre os modelos estudados, vale evidenciar que todos se destacaram em métrica em particular. Dentre os destaques estão:

  - **Modelo 5 Colunas com KBest**: Obteve uma precisão de 91.23%;
  - **Modelo 5 Colunas com RFE**: Obteve uma precisão de 96.49%;
  - **Modelo 23 Colunas com RFECV**:  Obteve uma precisão de 95.91%;
  - **Modelo 28 Colunas**:  Obteve uma precisão de 97.66%;

E para a vizualização dos dados de alta dimensionalidade, foram utilizadas os seguintes módulos:
- **Visualização de Dados com PCA**;

<h1 align="center">
  <img alt="Imagem Demonstrativa 1" title="#Img1" src="https://user-images.githubusercontent.com/33897566/228349075-7724a146-13ed-4e50-b30e-0de3d2f2171e.PNG" style="width: 800px;" />
</h1>

- **Visualização de Dados com T-SNE**;

<h1 align="center">
  <img alt="Imagem Demonstrativa 1" title="#Img2" src="https://user-images.githubusercontent.com/33897566/228349095-d0f66bbb-d840-40e1-9de5-34b59ba696b2.PNG" style="width: 800px;" />
</h1>


---

## 🛠Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

-   [Python](https://www.python.org/)
-   [SKLearn](https://scikit-learn.org/stable/user_guide.html)
-   [Seaborn](https://seaborn.pydata.org)
-   [SelectKBest](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SelectKBest.html)
-   [RFE](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html)
-   [RFECV](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFECV.html)
-   [T-SNE](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html)
-   [PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
-   [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)

---

## 📝Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Matheus Pereira 👋🏽 [Entre em contato!](www.linkedin.com/in/matheus-de-medeiros-pereira-52b245140)
