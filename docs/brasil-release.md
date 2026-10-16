# Home Tasks Brasil 2.4.1

Fork independente de [L3t4l3s/home-tasks](https://github.com/L3t4l3s/home-tasks),
baseado na versão 2.4.0 e distribuído sob a licença MIT original.

- Português brasileiro no card, editor e configuração da integração.
- Uma fonte JSON compartilhada para as traduções do frontend e do calendário.
- Descrições do calendário nos 16 idiomas e variantes disponíveis no card.
- Nome da pessoa atribuída no calendário, com ID como alternativa.
- Títulos, notas, etiquetas, datas e recorrências das tarefas preservados.

O card segue o idioma do perfil do usuário. O calendário segue o idioma geral
da instância do Home Assistant. Esta versão não adiciona interpretação de
comandos de voz em português.

## Instalação pelo HACS

1. No HACS, abra **Repositórios personalizados**.
2. Adicione `https://github.com/Willyanlz/home-tasks` na categoria **Integração**.
3. Baixe **Home Tasks Brasil** e reinicie o Home Assistant.
4. Adicione a integração em **Configurações → Dispositivos e serviços**.
5. Use o card `custom:home-tasks-card` normalmente.

Este fork usa o mesmo domínio `home_tasks` do projeto original: ele substitui
essa instalação, não funciona como uma segunda cópia em paralelo. Para migrar,
tenha um backup e preserve as entradas da integração e suas listas; troque a
origem de download no HACS para este fork.

As alterações também foram propostas ao projeto original no
[PR #71](https://github.com/L3t4l3s/home-tasks/pull/71). A existência desta release
não significa aprovação ou suporte do mantenedor original. Questões específicas
deste fork devem ser encaminhadas ao responsável pelo Home Tasks Brasil.
