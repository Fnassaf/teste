# teste

Este repositório inclui um exemplo de configuração do ESPHome para um Sonoff Mini. O arquivo `sonoff_mini.yaml` contém as diretivas necessárias para compilar e instalar o firmware no dispositivo.

O exemplo também mostra como usar condicionais de tempo para redirecionar o comando do botão. Se o dispositivo for acionado entre meia-noite e seis da manhã, ele não liga o próprio relê e sim o Sonoff denominado "closet" por meio de uma chamada de serviço ao Home Assistant.
