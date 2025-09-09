# projeto api de moedas
O projeto é um aplicativo web feito com Streamlit que permite consultar a cotação de diferentes moedas em relação ao Real usando a AwesomeAPI.

Como funciona:

O usuário abre o app no navegador e vê um título indicando que é um conversor/cotação de moedas.

É apresentado um menu de seleção com as opções: Dólar, Euro, Bitcoin e Libra.

O usuário escolhe a moeda desejada e clica no botão para buscar a cotação.

O app envia uma requisição à API para obter os dados da moeda selecionada.

Se a requisição for bem-sucedida, o app exibe:

- Nome da moeda
- Alta e baixa do dia
- Variação
- Cotação de compra e venda

Caso haja algum erro na requisição, uma mensagem de erro é exibida.

Observações:

- O app precisa de internet para funcionar, pois depende da API.
- Ele é simples, mas permite visualizar a cotação em tempo real de forma prática e rápida.
