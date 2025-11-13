# Instruções para Acessar os Contatos

## Como visualizar os contatos recebidos

Os contatos enviados pelo formulário do site são salvos localmente no navegador de cada visitante. Para acessar e gerenciar os contatos:

### Opção 1: Página de Administração (Recomendado)

1. Acesse: `https://thigil15.github.io/Jornadadagraca/admin.html`
2. A página mostrará todos os contatos enviados
3. Você pode:
   - Exportar os contatos para JSON
   - Copiar dados individuais
   - Excluir contatos específicos
   - Limpar todos os contatos

### Opção 2: Console do Navegador

1. Abra o site principal
2. Pressione F12 (ou Cmd+Option+I no Mac)
3. Vá para a aba "Console"
4. Digite: `JSON.parse(localStorage.getItem('jornada-contacts'))`
5. Pressione Enter para ver todos os contatos

### Opção 3: GitHub Issues

Se habilitado, os contatos também são criados como Issues no repositório GitHub. Acesse:
`https://github.com/Thigil15/Jornadadagraca/issues?q=label%3Acontact-form`

## Estrutura dos Dados

Cada contato contém:
- **nome**: Nome completo
- **email**: Endereço de email
- **telefone**: Número de telefone
- **necessidade**: Tipo de ajuda (Oração, Ajuda, Estudos Bíblicos, Visita, Outros)
- **outrosTexto**: Descrição adicional (quando aplicável)
- **dataHora**: Data e hora do envio

## Exportar para JSON

Na página de administração, clique em "📥 Exportar JSON" para baixar um arquivo JSON com todos os contatos.

## Backup Regular

É recomendado fazer backup regular dos contatos exportando o JSON periodicamente, pois os dados são armazenados localmente no navegador.

## Privacidade

⚠️ **IMPORTANTE**: Os dados dos contatos contêm informações pessoais. Trate-os com confidencialidade e respeito à privacidade dos usuários.
