# neural-network-chest-images
Projeto com duas redes neurais, MLP e CNN, para a criação de um modelo de predição para identificar se um paciente possui pneumonia.

Técnicas de Aprendizado Profundo foram usadas para criar dois modelos capazes de classificar imagens de raio-X da doença Pneumonia em “NORMAL” ou ”PNEUMONIA”, com o objetivo de auxiliar no processo de diagnóstico médico. Sendo assim, a capacidade dos modelso desenvolvidos em reconhecer padrões presentes nas imagens foram avaliada, a fim de atestar a sua eficiência como ferramenta de apoio ao diagnóstico.

Utilizou-se o dataset “Chest X-Ray Images (Pneumonia)”, disponibilizado na plataforma Kaggle. O conjunto de dados contém imagens de radiografias do tórax já classificadas nas duas categorias antes citadas. O dataset também já está dividido em conjuntos de treinamento, validação e teste, no entanto, não usaremos esse conjunto de validação já pronto devido ao pequeno tamanho do mesmo.

O primeiro modelo criado foi uma Rede Neural Perceptron Multicamadas (MLP) e o segundo foi uma Rede Neural Convolucional (CNN)
