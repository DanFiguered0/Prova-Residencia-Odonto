# Auditoria — 26/10/2026

## Escopo realizado

- Preservadas as 600 questões, com IDs 1–600.
- Corrigido o carregamento estático e mantida a ordem `questions.js` antes de `script.js`.
- Implementada correção imediata e bloqueio no estudo; justificativa específica da alternativa selecionada é exibida antes do gabarito.
- Implementada prova independente com 20 questões específicas, 5 SUS e 5 Português, sorteadas sem repetição, cronômetro opcional e gabarito oculto até finalizar.
- Implementadas tentativas independentes de revisão de erros, histórico, filtros e navegação, desempenho por área, exportação/importação JSON e migração do armazenamento v1 para v2.
- Preservação de dados anteriores: o script não apaga a chave v1, nem reinicia respostas na atualização.

## Alteração acadêmica fundamentada

- **Questão 181:** referência bibliográfica alterada de Bourguignon et al. (diretriz IADT para fraturas/luxações) para **Fouad AF et al. International Association of Dental Traumatology guidelines for the management of traumatic dental injuries: 2. Avulsion of permanent teeth. Dental Traumatology. 2020;36:331–342.** O tema da questão é avulsão de dente permanente. Enunciado, gabarito e justificativas foram mantidos.

## Alertas de conteúdo

- Possível repetição conceitual entre 109, 193 e 238 (úlcera lingual endurecida e investigação oncológica); entre 20 e 133 (cisto dentígero); e entre 143 e 169 (febre neutropênica). **Não foram reescritas sem revisão clínica independente**.
- Questões 488 e 495 cobram regências distintas, não sendo duplicatas literais.
- Distribuição declarada de dificuldade: 2 intermediárias, 318 difíceis, 280 muito difíceis. **Não houve reclassificação artificial**.
- As referências de todas as 600 questões não foram conferidas individualmente contra obras e legislação atualizada. Campos preenchidos não significam verificação bibliográfica.
- A análise independente dos 600 gabaritos, da precisão clínica e das duplicações semânticas permanece pendente.

## Testes

- Teste estático: JavaScript válido (`node --check`); 600 IDs únicos/sequenciais; 4 opções e 4 justificativas; gabaritos no intervalo 0–3; campos obrigatórios presentes; distribuição 334/183/83.
- Teste de navegador automatizado: **não concluído**. O Chromium disponível bloqueou a navegação para arquivo local e servidor local com `ERR_BLOCKED_BY_ADMINISTRATOR`. Assim, interações, persistência real e responsividade não foram certificadas em navegador.
- GitHub Pages: caminhos relativos e ausência de dependências externas verificados estaticamente; publicação real não testada.

## Pendências prioritárias

1. Testes em navegador real de correção, prova, revisão, exportação/importação e migração v1, incluindo celular.
2. Auditoria acadêmica independente de cada questão e referência, especialmente pares semelhantes acima.
3. Conferência de versões oficiais de normas e do Anexo X do edital.
4. Revisão da dificuldade real e acessibilidade completa.
