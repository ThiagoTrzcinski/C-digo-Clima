# Código-Clima

Descrição
Pequeno código monolítico que demonstra o clima na cidade de Videira, SC. Utiliza a API OpenWeatherMap para obter dados meteorológicos em tempo real.

Estrutura do Documento HTML
O site foi construído usando uma estrutura HTML simples, com um título no meio da página seguido por uma caixa de informações contendo os dados recebidos da API. Para tornar a visualização mais agradável foi criado um simples CSS que define estilos para a página, cabeçalho e caixa de informações meteorológicas.

Um Script JavaScript foi usado para a declaração das variáveis: apiKey, latitude, longitude, e apiUrl para a API OpenWeatherMap. E para criar getWeather(): Função assíncrona que faz uma requisição à API, obtém dados meteorológicos e atualiza a interface com as informações.

API OpenWeatherMap
A URL da API é construída com a chave de API, coordenadas geográficas, unidade métrica e a definição do idioma para português.
Utiliza a função fetch para fazer a requisição assíncrona.
Atualiza o conteúdo da caixa de informações com a temperatura e a condição meteorológica obtidas da resposta da API.
Os dados para a utilização da API foram obtidos em: https://openweathermap.org

Manipulação de Erros
Em caso de erro na obtenção dos dados, uma mensagem de erro é exibida no console.
