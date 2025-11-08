# skills-copilot-codespaces-vscode
My clone repository

## Ambiente de desenvolvimento

- Este projeto é desenvolvido em um Dev Container (Ubuntu 24.04.2 LTS).
- Para abrir o projeto no navegador do host (a partir do container), use:
  ```
  "$BROWSER" <url>
  ```

## Como executar localmente (exemplo)

1. Reabra o projeto no Dev Container via VS Code (Remote - Containers).
2. Instale dependências (ajuste conforme a stack do projeto):
   - Node: `npm install`
   - Python: `pip install -r requirements.txt`
3. Execute a aplicação:
   - Node: `npm start`
   - Python: `python -m <seu_pacote>`
4. Abra no navegador:
   ```
   "$BROWSER" http://localhost:3000
   ```

## Testes

- Comando genérico para rodar testes (ajuste conforme o projeto):
  - Node: `npm test`
  - Python (pytest): `pytest`
- Configure a task no VS Code para facilitar execução de testes a partir da interface.

## Contribuição

- Abra uma issue antes de iniciar alterações significativas.
- Envie PR com commits pequenos e mensagens claras.
- Inclua testes quando possível e atualize o README se necessário.

## Contato

- Para dúvidas rápidas, abra uma issue no repositório ou envie PR com a proposta de alteração.
