# project_currency_converter_api
# Conversor de Moedas

Este projeto é um conversor de moedas simples feito em HTML, CSS e JavaScript. Ele utiliza a API [ExchangeRate-API](https://www.exchangerate-api.com/) para buscar taxas de câmbio em tempo real entre Dólar (USD), Euro (EUR) e Real (BRL).

## Funcionalidades

- Conversão instantânea entre USD, EUR e BRL.
- Interface simples e responsiva.
- Validação de entrada e mensagens de erro amigáveis.

## Como usar

1. **Clone ou baixe este repositório.**
2. Abra o arquivo `index.htm` em seu navegador.
3. Insira o valor, selecione as moedas de origem e destino e clique em **Converter**.
4. O resultado aparecerá logo abaixo do formulário.

## Estrutura dos arquivos

- `index.htm`: Estrutura HTML da aplicação.
- `style.css`: Estilos para a interface (opcional).
- `script.js`: Lógica de conversão e integração com a API.

## Observações

- É necessário acesso à internet para buscar as taxas de câmbio.
- A chave da API está definida diretamente no arquivo `script.js`. Para uso em produção, recomenda-se proteger a chave.

## Exemplo de uso

```
Valor: 100
De: USD
Para: BRL

Resultado: 530.00 BRL
```