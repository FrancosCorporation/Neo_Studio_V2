# Melhorias — Neo Studio V2

## Implementado nesta revisão

- [x] Adicionar CI estática em Ubuntu 24.04 para analisar sintaxe dos arquivos Python e JSON nas versões Python 3.10 e 3.12.
- [x] Limitar o token padrão do workflow a `contents: read`.

## Verificações pendentes

- [ ] Validar a aplicação em Windows com os backends locais configurados.
- [ ] Validar os fluxos de imagem, vídeo e voz nas GPUs/modelos compatíveis.
- [ ] Executar a suíte de testes numa tarefa autorizada; esta revisão não adicionou nem executou testes.

A CI adicionada só analisa sintaxe e configuração. Não instala dependências,
abre serviços ou executa workflows de geração.
