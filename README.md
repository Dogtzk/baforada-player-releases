# Baforada Player

Distribuição do player feito por dogtzk. O nome e os temas dentro do aplicativo continuam como estão.

## Baixar para Windows

[Baixar a versão mais recente](https://github.com/Dogtzk/baforada-player-releases/releases/latest)

Baixe o arquivo **BaforadaPlayer-Setup-VERSÃO.exe** e execute o instalador. Não precisa extrair ZIP.

Se já usava a versão ZIP, escolha a pasta onde está **VibePlayer.exe** para manter também a biblioteca e os downloads locais. Na mesma conta do Vibe, playlists e capas sincronizam entre os aparelhos.

## Baixar para Android

[Baixar APK Android 1.6.26](https://github.com/Dogtzk/baforada-player-releases/releases/download/v1.8.30/BaforadaPlayer-Android-1.6.26.apk)

Compatível com Android 9 ou superior. Baixe e abra o APK no celular para instalar ou atualizar. O nome dentro do app permanece igual.

## Atualizações no Windows

Depois da primeira instalação, o aplicativo verifica novas versões automaticamente a cada 30 minutos, mesmo minimizado. Um ponto laranja no ícone de Configurações indica que há uma atualização disponível. Em **Configurações → Atualizações do aplicativo**, escolha **Baixar atualização** e depois **Instalar e reiniciar**. Os arquivos baixados, as playlists e as configurações são mantidos. As atualizações futuras serão disponibilizadas por este mesmo repositório; não é necessário reenviar arquivos aos amigos.

Este repositório contém apenas instruções e arquivos de distribuição. Bibliotecas pessoais, senhas, tokens e a chave privada de publicação não são enviados.

### Atualização no Android

A partir do Android 1.6.12, o aplicativo avisa em Ajustes e permite baixar novas versões. O Android pede sua confirmação para instalar. Quem usa uma versão anterior precisa instalar o APK 1.6.6 uma vez, mantendo o app instalado para preservar os dados. Compatível com Android 9 ou superior.

### Temas personalizados

Em Temas → Criar +, personalize cores, fotos de banner e fundos, fonte, ícones, nome e aparência do player com prévia ao vivo. Salve, edite, duplique ou exclua seus temas. Os temas ficam salvos neste aparelho e acompanham a exportação da biblioteca. Disponível no Windows 1.8.8 e Android 1.6.12.

### Kanye West

Novo tema em cinco variações: Graduation, 808s & Heartbreak, Yeezus, The Life of Pablo e The College Dropout. Capas locais, paletas e ícones próprios. Disponível no Windows 1.8.9 e Android 1.6.12.

Imagens do tema Kanye West integradas ao banner com fade no Windows 1.8.10 e Android 1.6.12.

Arte completa no tema Kanye West: sem zoom nem cortes, com extensão desfocada e fade no fundo. Windows 1.8.11 e Android 1.6.12.

### Buscar pela letra

Use a mesma barra e selecione **Pela letra**, ou digite **letra:** antes do trecho. O app mostra possíveis músicas e versões dos artistas. O Windows também ganhou reconexão ao Discord, renovação da atividade, botões alinhados, capas preenchidas e ícones nativos por tema. A confirmação de recebimento do Discord não garante a visibilidade no perfil.

### Ícones e reprodução

Windows 1.8.15: ursinhos Dropout Bear apenas nos ícones da barra de tarefas do Kanye West; banner preservado. Aleatório sem repetição dentro do ciclo e ordem inteligente com prevenção de fontes de áudio duplicadas, também no Android 1.6.12.

### Início, recomendações e fila

Windows 1.8.17 e Android 1.6.13: tela Início com atalhos, recentes, redescobertas e sugestões parecidas com seus artistas. Recomendações em cada playlist com botão Adicionar. Novo painel de fila com histórico e cartão A seguir no Tocando agora.

### Seleção em lote e capas

Windows 1.8.18 e Android 1.6.14: em Selecionar músicas, marque faixas da biblioteca, playlists ou resultados de busca e use Baixar selecionadas ou Adicionar à playlist. Selecionar tudo inclui as faixas além da página visível; no PC, Shift seleciona intervalos. Capas com bordas pretas em fontes compatíveis são recortadas apenas na exibição, preservando o arquivo original.

### Perfil mensal e fontes indisponíveis

Windows 1.8.19 e Android 1.6.15: foto, nome e descrição do perfil junto ao resumo mensal. Fontes indisponíveis são puladas sem remover as músicas da playlist, com proteção contra listas sem faixas reproduzíveis e resultados atrasados de outra escolha. No Windows, botões da fila e Tocando agora com o mesmo tamanho e estilo.

### Cache, busca e reprodução — Windows 1.8.21 / Android 1.6.17

Cache persistente de fontes públicas com expiração e invalidação. Primeiro play usa consulta leve e conexão preparada, com repetição em falhas transitórias. Menos trabalho na interface e processos auxiliares limitados. Busca reconhece títulos em japonês escritos em letras latinas quando os metadados confirmam a equivalência e preserva o canal oficial. Setas nas extremidades das listas horizontais, ajustes no relógio e seleção de letras sincronizadas, Top 10 mensal e artistas mais ouvidos. Android 1.6.17. Biblioteca e personalizações preservadas. Nos testes normais do Windows, início em 0,32 s e reabertura com cache em 0,06 s. A demora observada durante compilação simultânea ainda está em investigação; não há garantia desse tempo sob carga ou em outras conexões.

### Cache, busca e reprodução — Windows 1.8.22 / Android 1.6.18

Corrigido carregamento de fotos de artistas pelo CDN atual da Wikimedia, incluindo Radiohead. Reconhecimento de bandas descritas como trio ou duo. Quando não há foto no Wikidata, o app procura a imagem do canal oficial confirmado; imagens indisponíveis mostram um ícone sem texto alternativo quebrado. Início da música atualiza apenas os cartões recentes necessários e mantém as recomendações existentes. Conversão de capa para controles de mídia usa codificação assíncrona, e no Windows, processos auxiliares de recomendações recebem prioridade reduzida. Inclui Android 1.6.18. Biblioteca, conta, temas e downloads preservados. Picos dependentes de decodificação e carga do sistema ainda podem ocorrer.

### Cache, busca e reprodução — Windows 1.8.23 / Android 1.6.19

No Início, Tocadas recentemente mostra uma seleção aleatória de até oito músicas ouvidas nos últimos 30 dias, incluindo o modo inteligente; curtir sem ouvir não adiciona músicas. Botão Sortear novamente e seleção estável durante a reprodução. Recomendações consultam o catálogo e o mix público diretamente, sem iniciar o extrator externo. A análise de estilo deixa de resolver fontes de áudio completas de várias músicas ainda não tocadas, usa consultas leves e reaproveita resultados simultâneos; falhas de metadados têm cache curto para evitar repetição contínua. As buscas manuais e a reprodução mantêm suas alternativas de fonte. Inclui as fotos de artistas corrigidas, alternativa do canal oficial, proteção para imagens indisponíveis, atualização parcial dos cartões recentes e capa dos controles de mídia codificada de forma assíncrona. Android 1.6.19. Biblioteca, conta, temas e downloads preservados. Esta mudança remove trabalho desnecessário de fundo; decodificação do áudio e carga do sistema ainda podem causar picos breves. Fontes alternativas exigem formato somente de áudio, evitando baixar e decodificar vídeo desnecessariamente.

### Cache, busca e reprodução — Windows 1.8.24 / Android 1.6.20

No Windows, retornar a uma faixa durante o fade cancela seu encerramento antigo; o temporizador não pode parar o áudio ativo. Recuperação limitada de pausas técnicas inesperadas, respeitando pausas feitas no app ou pelas teclas de mídia. A ordem inteligente valida subgêneros antes das respostas parciais e da seleção local, evitando tratar emo, hard rock e metal como equivalentes e impedindo deriva de estilo pelo mix ou pela próxima faixa. Consultas de metadados limitadas e com cache, sem reintroduzir o extrator pesado nas recomendações. Perfis oficiais dos artistas têm prioridade sobre fotos da Wikimedia; canais oficiais de artista precedem Topic. Inclui Android 1.6.20. Biblioteca, temas, conta e downloads preservados.

### Artistas, amigos e playlists — Windows 1.8.25 / Android 1.6.21

Páginas de artistas com foto, apresentação, músicas e discografia. Abra um álbum para consultar e tocar suas faixas usando as fontes completas disponíveis. Siga artistas e amigos pela conta do player; busque amigos pelo nome de usuário em Artistas e amigos. Foto e apresentação públicas são opcionais e publicadas apenas pelo próprio usuário; biblioteca, curtidas e histórico permanecem privados. Recursos disponíveis no PC e Android 1.6.21, com sincronização dos artistas e amigos seguidos. Mantém as correções de reprodução, ordem inteligente e fotos oficiais da versão anterior. Cabeçalho de playlist redesenhado com capa e título lado a lado, ações alinhadas e organização responsiva. Botão de repetir à direita, logo após o botão de próxima música, com estado visível e sincronizado.

### Navegação, perfil e busca — Windows 1.8.26 / Android 1.6.22

Navegação reorganizada: fila permanece na barra inferior e Seu mês em música fica no menu do perfil. Mais espaço na lateral para playlists, capas maiores e itens alinhados. Perfil redesenhado com foto, apresentação e atalhos; sincronização e segurança em áreas recolhíveis. A busca principal agora mostra artistas e amigos, além das músicas, e permite abrir seus perfis. Amigos podem ser encontrados pelo nome público ou @usuário. Sugestões independentes, com cache e proteção contra respostas antigas; as consultas de amigos não bloqueiam a busca musical. Inclui Android 1.6.22. Biblioteca, temas, conta e downloads preservados.

### Modo imersivo e temas na conta — Windows 1.8.27 / Android 1.6.23

Temas personalizados sincronizam pela mesma conta, incluindo imagens, cores, ícones e edições. O tema escolhido continua independente por aparelho. Transferência de temas em lotes limitados por tamanho e armazenamento privado por usuário. Novo modo imersivo opcional: Barras de luz, Órbita, Aurora, Horizonte e Constelação, com análise do áudio real no PC e Android. Cores acompanhando a capa, intensidade e desfoque ajustáveis. Modo foco destaca capa e controles; opção de capa como vinil girando. Modo econômico de até 18 quadros por segundo, limite de resolução e animações interrompidas ao pausar ou colocar o app em segundo plano. Respeita movimento reduzido e não pede acesso ao microfone. Inclui Android 1.6.23. Biblioteca, downloads e conta preservados.

### Visualizador e organização de playlists — Windows 1.8.28 / Android 1.6.24

Visualizador corrigido: espectro desenhado dentro da área visível, sem barras dos graves cobertas pela lateral ou base escondida sob o player. Maior contraste no fundo do modo foco. Mensagem de estado nas configurações e opção explícita para respeitar ou permitir animação quando o sistema pede movimento reduzido. Organizar músicas agora mantém a faixa visível ao mover para posições distantes, usa páginas de até 60 faixas e oferece busca por música ou artista. Foco de teclado preservado, atalhos Alt+setas e proteção contra duplo clique que desfazia a movimentação. Confirmação de ordem gravada antes de fechar; falhas e mudanças concorrentes mantêm a edição disponível para revisão ou nova tentativa. A ordem manual é usada no modo Em ordem, indicado na janela. Inclui Android 1.6.24, com temas, biblioteca e conta preservados.

### Fontes e recuperação do áudio — Windows 1.8.29 / Android 1.6.25

No PC, os cabeçalhos da música atual e das faixas pré-carregadas são isolados por sessão de áudio, evitando interferência entre fontes. Monitoramento de reprodução travada: tentativa limitada de retomada e reconexão no mesmo ponto, respeitando pausa, retomada e troca de faixa. Falhas do dispositivo de áudio não marcam a música como indisponível. Indicação de carregamento e diagnóstico copiável em Configurações. Links do YouTube Music, mobile, Shorts, live e embed são normalizados; links compartilhados do SoundCloud são resolvidos quando disponíveis. Consulta de metadados usa a página pública como alternativa ao oEmbed, com mensagens específicas da plataforma. Invalidação de fontes limpa a resolução antiga e não permite que pedidos anteriores restaurem cache obsoleto; validade de URLs temporárias é verificada. Transporte de rede preservado na recuperação e no SoundCloud. Inclui Android 1.6.25 com as correções compartilhadas de links e fontes.

### Jam para ouvir junto — Windows 1.8.30 / Android 1.6.26

Jam para ouvir junto no PC e Android: sala por código ou link que abre o aplicativo instalado, convites para os amigos seguidos e aviso de convites dentro do player. O anfitrião controla reprodução, pausa, posição e próxima faixa; convidados adicionam músicas à fila compartilhada e podem pausar só a própria escuta. Volume independente, entrada no ponto atual da música e correção de diferença de tempo. Reconexão e tentativa individual de uma fonte indisponível sem trocar a música da sala. Ao sair, a seleção anterior do convidado é restaurada pausada. Até 16 aparelhos por sala, com duração de até 6 horas. Cada aparelho precisa de internet e de acesso à fonte pública; a precisão depende da rede e do áudio disponível. Inclui Android 1.6.26.
