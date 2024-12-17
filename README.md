# Sistema de Estimativa de Peso de Gado Usando ResNet152 e PyTorch.

Este é um modelo de regressão projetado para estimar o peso do gado com base apenas em suas imagens. Diante das limitações de qualidade e tamanho do conjunto de dados, bem como restrições computacionais com uma GPU de 3GB, foi necessária uma abordagem leve, porém eficaz.
Para superar esses desafios, implementei transfer learning utilizando o modelo ResNet152 do PyTorch. Ao aproveitar a arquitetura pré-treinada da ResNet152, consegui adaptá-la para tarefas de regressão, permitindo previsões precisas de peso, mantendo as demandas computacionais sob controle.
Essa solução equilibra eficiência e precisão, demonstrando como o transfer learning pode ser aplicado de forma eficaz mesmo em ambientes com recursos limitados. É notável que o sistema convergiu, atingindo um MAE de 5% do valor do peso do animal.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Cattle Weight Estimation System Using ResNet152 and PyTorch

This is a regression model designed to estimate cattle weight based solely on their images. Given the limitations of the dataset's quality and size, as well as computational constraints with a 3GB GPU, a lightweight yet effective approach was necessary.
To overcome these challenges, I implemented transfer learning using the ResNet152 model from PyTorch. By leveraging the pre-trained ResNet152 architecture, I adapted it for regression tasks, enabling accurate weight predictions while keeping computational demands manageable.
This solution balances efficiency and accuracy, demonstrating how transfer learning can be effectively applied even in resource-constrained environments. Notably, the system converged, achieving a Mean Absolute Error (MAE) of 5% of the animal's weight value.
