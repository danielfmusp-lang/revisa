# Revisa — versão inicial

## O que já funciona
- Painel responsivo para celular e computador.
- Checklist diário inicial, com possibilidade de adicionar tarefas.
- Filtros: tudo, pendentes e concluídas.
- Revisões espaçadas configuráveis para 7, 14 ou 21 dias.
- Registro de minutos estudados e observações por matéria.
- Caderno de erros com motivo do erro, plano de correção e status.
- Registro de treinos de questões com taxa de acerto acumulada.
- Resumo de tempo por matéria nos últimos sete dias e sequência de dias.
- Timer de foco de 25 minutos.
- Exportar/importar backup JSON.
- Salva dados no navegador/dispositivo (localStorage).

## Como abrir
1. Extraia o ZIP.
2. Abra `index.html` no navegador para testar as funções principais.
3. Para instalar como PWA e usar offline, publique os arquivos em um host HTTPS (por exemplo, GitHub Pages ou Netlify) e abra o site no celular; o suporte à instalação varia por navegador.

## Limitações importantes desta primeira versão
- Ainda não há login nem sincronização entre dispositivos.
- Google Calendar não está conectado. Isso requer configuração OAuth segura e um backend ou integração autorizada; não coloque segredos no HTML.
- O timer não bloqueia sites/aplicativos.
- Os dados ficam no navegador. Use Exportar dados para criar backups regularmente.
- O plano diário inicial é apenas um modelo editável, não um cronograma oficial atualizado de provas.

## Próximas etapas sugeridas
1. Publicar num endereço HTTPS.
2. Adicionar login e sincronização segura.
3. Integrar Google Calendar com autorização explícita.
4. Adicionar importação de questões, caderno de erros e estatísticas por assunto.
