Descrição
Benevolente Audio and Lyrics é um reprodutor de música web que sincroniza legendas com a reprodução de áudio em tempo real. Aplicação web pura que funciona completamente no navegador sem necessidade de conexão à internet ou instalação.

Funcionalidades
Reprodução de formatos MP3, WAV, OGG

Sincronização de legendas nos formatos LRC e TXT

Interface responsiva para desktop e mobile

Modo tela cheia para legendas

Upload por arrastar e soltar

Controles de reprodução completos

Como Usar
Requisitos
Navegador moderno (Chrome, Firefox, Safari, Edge)

JavaScript habilitado

Instalação
Baixe o arquivo index.html

Abra no navegador de sua escolha

Uso Básico
Clique em "Selecionar Arquivos" ou arraste arquivos para a área designada

Selecione arquivos de áudio (.mp3, .wav, .ogg) e legendas (.lrc, .txt)

Clique em uma música na playlist para reproduzir

Use os controles para play/pause, volume e navegação

Clique em "Tela Cheia" para modo imersivo de legendas

Formato de Legendas
Formato LRC (Recomendado):
[mm:ss.xx] Texto da legenda
Exemplo: [01:23.45] Linha da letra

Formato TXT Simples:
segundos Texto da legenda
Exemplo: 83.45 Linha da letra

Convenção de Nomes
Para sincronização automática, use o mesmo nome para áudio e legenda:

musica.mp3

musica.lrc

Estrutura do Projeto
index.html - Arquivo principal (contém HTML, CSS e JavaScript)

README.md - Documentação do projeto

Tecnologias Utilizadas
HTML5

CSS3 (Grid, Flexbox, Variables)

JavaScript ES6+

Web Audio API

File API

Características Técnicas
Single HTML file architecture

Funciona offline após carregamento

Sem dependências externas

Totalmente responsivo

Suporte a teclas de atalho

Atalhos de Teclado
Espaço: Play/Pause

Seta Esquerda: Música anterior

Seta Direita: Próxima música

ESC: Sair do modo tela cheia

Solução de Problemas
Legendas não aparecem:
Verifique se os nomes dos arquivos correspondem

Confira o formato do arquivo de legenda

Certifique-se de usar timestamps no formato correto

Áudio não reproduz:
Verifique o volume do navegador

Confira se o formato do arquivo é suportado

Tente outro navegador

Arquivos não carregam:
Use arquivos menores que 50MB

Tente um arquivo de cada vez

Verifique permissões do navegador

Personalização
As cores do tema podem ser modificadas editando as variáveis CSS na seção :root do arquivo.

Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para detalhes.

Suporte
Para reportar bugs ou sugerir melhorias, abra uma issue no repositório do projeto.
