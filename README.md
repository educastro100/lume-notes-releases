# Lume Notes

**Um espaço tranquilo para escrever.**

O Lume é um editor de texto e Markdown para **Windows x64**, pensado para rascunhar ideias, organizar documentos e escrever com menos distrações. Suas notas ficam no computador, sem precisar de uma conta para usar o aplicativo.

**[Baixar a versão mais recente](https://github.com/educastro100/lume-notes-releases/releases/latest)**

## O que você pode fazer

- **Escrever em texto ou Markdown:** edite com a formatação visível ou veja o código Markdown com uma prévia ao lado.
- **Formatar suas notas:** negrito, itálico, sublinhado, código, títulos, listas com marcadores e números, citações, tabelas e listas de tarefas.
- **Organizar documentos em abas e grupos:** escolha nomes e cores, recolha grupos, mova arquivos por arraste e selecione vários documentos de uma vez.
- **Retomar de onde parou:** o Lume recupera abas, rascunhos, grupos e preferências ao abrir novamente.
- **Personalizar o espaço:** temas de cor, tema automático pelo horário, tamanho da fonte, ícones por documento e painéis redimensionáveis.
- **Entrar no modo foco:** expanda a área de escrita e recolha os controles com uma transição suave.
- **Encontrar e revisar:** busca, substituição, contagem de palavras e caracteres e histórico de desfazer e refazer durante a sessão.
- **Usar seus arquivos locais:** abra e salve documentos de texto, Markdown, JSON, logs e outros formatos de texto. O modo de código também destaca JavaScript/TypeScript e JSON.
- **Integrar com o Windows:** use Abrir com Lume e escolha o aplicativo como padrão nas configurações do próprio Windows.
- **Escolher seu idioma:** português do Brasil, inglês, francês, alemão, grego ou chinês simplificado.
- **Atualizar pelo aplicativo:** verifique novas versões e instale a atualização pelo Lume.

## Como o Lume guarda seus textos

As notas e os rascunhos são locais. O aplicativo não exige cadastro e não oferece sincronização na nuvem. A consulta de atualizações usa este canal público do GitHub; o conteúdo das suas notas não é enviado nessa consulta.

A recuperação de rascunhos ajuda a retomar o trabalho, mas **não substitui salvar o arquivo original**. Use Salvar ou Salvar como para gravar suas alterações em disco.

## Como baixar e instalar

1. Clique em **[Baixar a versão mais recente](https://github.com/educastro100/lume-notes-releases/releases/latest)**.
2. Na página da versão, procure a seção **Assets**, abaixo das notas da atualização. Se ela estiver fechada, clique para expandir.
3. Baixe o arquivo **`Lume-Notes-<versão>-Windows-x64-setup.exe`**. Por exemplo: `Lume-Notes-0.9.1-Windows-x64-setup.exe`.
4. Abra o arquivo `.exe` baixado e siga as instruções do instalador.

Na página inicial deste repositório, você também pode acessar a versão pela seção **Releases**, na lateral direita. Não é necessário ter uma conta no GitHub para baixar.

## Já tem o Lume instalado?

No aplicativo, use **Verificar atualização** para procurar uma versão mais recente e seguir o fluxo de atualização. Você também pode baixar o novo instalador pela página de Releases.

## Qual arquivo devo baixar?

Para instalar o Lume, você precisa apenas do arquivo que termina em **`-setup.exe`**.

| Arquivo em Assets | Para que serve |
| --- | --- |
| `Lume-Notes-<versão>-Windows-x64-setup.exe` | Instalador do Lume para Windows x64. **Baixe este arquivo.** |
| Arquivo terminado em `.exe.sig` | Assinatura usada para verificar a atualização. |
| `latest.json` | Informações de versão e download consultadas pelo atualizador do aplicativo. |
| `SHA256SUMS.txt` | Hashes para conferir a integridade dos arquivos. |
| `Source code (zip)` e `Source code (tar.gz)` | Arquivos gerados pelo GitHub a partir deste repositório de distribuição; não são instaladores. |

Este repositório contém os instaladores e os metadados de atualização. O código-fonte do aplicativo é mantido em um repositório privado.

## Atalhos mais comuns

| Ação | Atalho |
| --- | --- |
| Nova nota | Ctrl + N |
| Abrir arquivos | Ctrl + O |
| Salvar | Ctrl + S |
| Salvar como | Ctrl + Shift + S |
| Fechar a aba atual | Ctrl + W |
| Buscar e substituir | Ctrl + F |
| Negrito / itálico / sublinhado | Ctrl + B / Ctrl + I / Ctrl + U |
| Código em linha ou bloco | Ctrl + Shift + C |
| Desfazer / refazer | Ctrl + Z / Ctrl + Y |
| Modo foco | F8 |

## Ajuda, problemas e sugestões

Encontrou um problema ou tem uma ideia para o Lume? Abra uma **[issue neste repositório](https://github.com/educastro100/lume-notes-releases/issues)**. Informe a versão do aplicativo, o que esperava que acontecesse e os passos para reproduzir o comportamento.

Não é necessário ter uma conta no GitHub para baixar o instalador. Para criar uma issue, é necessário entrar na sua conta.

## Tecnologias

O Lume usa **Tauri 2 e Rust** na integração com o sistema, **React e TypeScript** na interface, **Tiptap/ProseMirror** na edição visual e **CodeMirror 6** na edição de código. As fontes e os ícones fazem parte da interface local.

## Em preparação: versão 0.10.0

A próxima versão reúne formatação combinada com código em linha, ajustes no espaçamento de listas, ajuda dentro das configurações, bandeiras nos idiomas, tema Manhã, cinco novos ícones e melhorias nos botões de abertura e nos avisos de formatação.

Esta seção descreve o que está em desenvolvimento. O link de download no início da página sempre leva à versão já publicada.
