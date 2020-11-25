Lauro Milagres Oliveira
Lucas Dutra Ponce Donoso de Leon

################################################################################
# 			Para compilar o projeto, use Jupyter 		       #
################################################################################

- jupyter notebook cnn_birads.ipynb


################################################################################
#    			Para Rodar com Modelo Treinado 			       #
################################################################################

Para rodar com o modelo já treinado, é necessario rodar apenas a celula dos imports
e a ultima celula responsavel por carregar o modelo.

Deve passar na mão o diretorio ou a imagem para ser classificada.


################################################################################

Este diretorio contem 5 pastas:

- dataset_train:
	* Pasta que deve ser colocada as imagens de treino em seus respectivos diretorios
	* Contem 4 subdiretorios (1,2,3,4)
- dataset_teste:
	* onde o proprio projeto adciona as imagens que estão no diretorio de traino
	* É reservado para 30% das imagens de traino
- dataset_validation:
	* Diretorio de validação com as imagens do diretorio de treino
	* É reservado para 70% das imagens de traino
- model:
	* Modelo treinado
- Treinos:
	* resultado de treinos com 2, 3 e 4 camadas
	* Não colocamos treinos com outros Hiperparametros
