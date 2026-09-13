# SupportPilot Desktop

Aplicativo para Windows 64 bits para organizar chamados, base de conhecimento, tablets, projetos, tarefas, calendário e notas.

Este repositório distribui os instaladores. O código-fonte e os dados dos usuários não fazem parte deste repositório.

## Instalar

1. Abra a seção **Releases** deste repositório.
2. Baixe o arquivo `SupportPilot-Desktop-Teste-0.2.0-Setup.exe` da versão desejada.
3. Execute o instalador e siga as instruções.

Não é necessário instalar Python, Node.js ou configurar um banco online. Esta é uma versão de teste, ainda sem certificado de assinatura digital.

## Clientes e lembretes

A versão 0.2.0 inclui cadastro de clientes com histórico de chamados, projetos e tablets. Os campos dos formulários sugerem os nomes já cadastrados.

Os lembretes aparecem 15 minutos antes dos compromissos, com atualização a cada 30 segundos. Mantenha o aplicativo aberto, inclusive minimizado. Para receber avisos do Windows, instale pelo instalador e permita notificações nas configurações do sistema. Compromissos cancelados ou atividades concluídas não geram novos avisos.

Para atualizar, exporte um backup, feche o aplicativo e instale no mesmo local da versão anterior.

## Dados e backup

Cada computador armazena seus próprios dados. Esta versão não sincroniza informações entre computadores.

Use o menu **Dados → Exportar backup** para guardar o banco e as imagens locais. Para levar os dados a outro computador, use **Dados → Restaurar backup** no aplicativo de destino. A restauração substitui os dados desse aplicativo após confirmação; não mescla bancos.

O menu **Dados → Abrir pasta dos dados** mostra o armazenamento local. Imagens antigas hospedadas no Supabase não são importadas automaticamente.
