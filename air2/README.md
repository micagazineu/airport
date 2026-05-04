# Airport Gap API Test Suite 2

Esta é uma segunda suíte de testes focada em cenários negativos e validações específicas.

## Testes incluídos:
- **Airports**: Busca por ID inválido (404) e validação do aeroporto GIG.
- **Favorites**: Acesso sem token (401) e listagem de favoritos.
- **Distance**: Cálculo com códigos IATA inexistentes (422).

## Como rodar:
1. cd air2
2. npm install
3. npm test
