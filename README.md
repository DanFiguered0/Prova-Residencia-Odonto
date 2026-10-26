# Simulado Residência CTBMF — HEAT/SES/RJ 2027

Projeto educacional independente, não oficial, com 600 questões. Para publicar no GitHub Pages, envie os cinco arquivos desta pasta para a raiz do repositório (ou mantenha a pasta como raiz da publicação) e habilite **Settings > Pages > Deploy from a branch**.

## Utilização

- **Modo estudo**: uma resposta por questão e correção imediata, com justificativa da alternativa escolhida primeiro.
- **Prova de 30 questões**: sorteio sem reposição de 20 específicas, 5 SUS e 5 Português. O gabarito permanece oculto até finalizar. Cronômetro configurável.
- **Refazer erros**: sessão independente das respostas incorretas da tentativa ativa.
- **Histórico**: tentativas concluídas ou arquivadas podem ser consultadas e revistas.
- **Progresso**: salvo em `localStorage` neste navegador; exporte periodicamente o JSON.

## Migração de versões

Na primeira abertura, se não houver progresso v2, o site tenta migrar dados da chave anterior `ctbmf-heat-2027-v1`. O original é preservado. Questões 501–600 são adicionadas como pendentes. A migração é local ao mesmo navegador e origem; mudar de domínio ou abrir um arquivo local não transfere automaticamente os dados. Para migrar entre origens, exporte o progresso antes e importe no novo endereço. A importação pede confirmação antes de substituir o estado.

## Limitações

A integridade estrutural das 600 questões foi verificada, mas não há revisão acadêmica independente integral. Confira o `RELATORIO_AUDITORIA.md` antes de usar o conteúdo para decisões clínicas ou normativas. O banco não substitui diretrizes oficiais.
