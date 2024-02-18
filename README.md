# Image Processing Package

Este é um pacote Python para processamento de imagens. Ele fornece uma variedade de funcionalidades para manipular imagens, aplicar filtros, realizar transformações e muito mais.

## Instalação

Você pode instalar o pacote via pip. Execute o seguinte comando:


## pip install image-processing-package

## Uso

Aqui está um exemplo básico de como você pode usar este pacote:

##python

from image_processing.filters import apply_grayscale, apply_blur
import cv2

# Carregar uma imagem
image = cv2.imread('example.jpg')

# Aplicar conversão para escala de cinza
gray_image = apply_grayscale(image)

# Aplicar um filtro de suavização
blurred_image = apply_blur(image)

# Exibir as imagens
cv2.imshow('Original Image', image)
cv2.imshow('Grayscale Image', gray_image)
cv2.imshow('Blurred Image', blurred_image)
cv2.waitKey(0)
cv2.destroyAllWindows() 




## Contribuindo
Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request no GitHub.



## License
Este projeto é licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter detalhes.
