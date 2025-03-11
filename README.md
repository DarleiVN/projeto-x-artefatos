# projeto-x-artefatos
requisitos/funcionais/
requisitos/nao-funcionais/
documentacao/manuais/
documentacao/diagramas/
testes/casos-de-teste/
testes/scripts/
codigo-fonte/frontend/
codigo-fonte/backend/
# Governança do Repositório  
- **Responsáveis:** Líderes de Projeto.  
- **Fluxo de Mudanças (ITIL):**  
  1. Propostas via *Pull Request*.  
  2. Aprovação de 2 revisores.  
- **Tags:** Use `v1.0.0` para versões e `aprovado` para status.
- name: Run Tests
on: [push]
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: Run Compliance Check
        run: echo "Verificando conformidade com ITIL/COBIT..."
  ## [1.0.0] - 2023-10-05  
### Added  
- Requisitos funcionais (RF-001 a RF-020).
  
