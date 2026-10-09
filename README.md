# Telon

Telão para cerimônias: vídeos de homenagem, fotos e música no segundo monitor, com transições suaves e operação simples.

## Baixar

Baixe o instalador mais recente em **[Releases](https://github.com/Attua-Victor/Telon-Resources/releases/latest)** — arquivo `Telon-Setup-x.y.z.exe`.

Requisitos: Windows 10 ou 11 (64 bits). Para usar o telão, conecte o projetor ou TV como segundo monitor.

## Instalação

1. Execute o `Telon-Setup-x.y.z.exe`.
2. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações → Executar assim mesmo**.
3. Siga o instalador. O atalho **Telon** é criado na área de trabalho e no menu Iniciar.

## Atualizações

O Telon verifica novas versões sozinho a cada hora e baixa em segundo plano. A atualização é instalada **quando o Telon é fechado** — nunca no meio de uma cerimônia. Se preferir, clique em **Reiniciar agora** no topo da janela quando o aviso aparecer.

## Uso rápido

| Tecla | Ação |
| --- | --- |
| `→` ou `Espaço` | Próximo item |
| `←` | Item anterior |
| `Enter` | Exibir o item selecionado |
| `P` | Pausar / continuar |
| `Esc` | Tela de descanso |
| `B` | Tela preta |

Arraste vídeos (MP4, MOV, WEBM) e fotos (JPG, PNG, WEBP) para a coluna **Roteiro**.

## Novidades

### 0.5.0 — 09/10/2026

- **Imagem de fundo na tela de descanso:** escolha uma imagem que cobre a tela inteira. A logo agora é opcional.
- **Música na tela de descanso:** toca em repetição enquanto o telão está no descanso, com volume próprio. Sai com fade quando entra um vídeo ou foto, volta de onde parou no descanso e fica em silêncio enquanto uma música do roteiro toca.
- **Fade ao repetir vídeo:** vídeos em "Repetir" escurecem e baixam o som no fim e voltam ao início suavemente, sem corte seco.
- A prévia da tela de descanso nas Configurações fica fixa no topo enquanto você rola os ajustes.

### 0.4.1 — 09/10/2026

- Corrigido: músicas novas no roteiro ignoravam o padrão e entravam sempre como "Parar no fim".
- Novo padrão **Músicas ao terminar** em Configurações → Roteiro (Próxima música, Repetir ou Parar no fim), separado do padrão de vídeos e fotos.

### 0.4.0 — 09/10/2026

- **Músicas no roteiro:** adicione MP3, WAV, M4A, OGG ou FLAC e elas tocam **por cima** do que estiver no telão (vídeo, foto ou tela de descanso), numa trilha de áudio própria.
- **Barra de música:** mostra a música tocando, o tempo e tem pausar, parar (com saída suave) e volume. Atalho **M** para parar a música.
- **Som do vídeo:** cada vídeo pode ficar com o som ligado ou mudo, para não brigar com a música.
- Ao terminar uma música: parar, repetir ou tocar a próxima música do roteiro. No avanço automático, as músicas entram junto com os vídeos e fotos.
- Seletor de telão redesenhado, com ícones e resolução de cada monitor.
- Corrigido o modal de Configurações que descia um pouco ao abrir a aba de Atualizações.

### 0.3.0 — 09/10/2026

- **Salvamento automático:** roteiro, item selecionado, transição e configurações são salvos a cada mudança, de um jeito que resiste a queda de energia. Se o Telon fechar sem querer com uma mídia no telão, ao reabrir ele oferece **retomar do ponto em que parou**.
- **Abre com o Windows:** o Telon abre sozinho quando o computador liga (dá para desligar em Configurações → Sistema).
- **Prévia ao vivo do telão:** a prévia agora espelha exatamente o que o público está vendo, inclusive tela de descanso, tela preta e transições. O item selecionado aparece num cartão no canto até ir para o ar.
- **Configurações em abas:** Tela de descanso, Roteiro, Sistema e Atualizações.
- **Aba de Atualizações:** botão para buscar atualizações na hora e histórico das versões com as novidades de cada uma.
- **Cor do brilho** da tela de descanso personalizável.
- Campos de número, seleção e controle deslizante redesenhados.

### 0.2.0 — 09/10/2026

- Novo botão de **Configurações** (engrenagem no canto superior direito).
- Tela de descanso personalizável: cor de fundo, logo própria, tamanho da logo e brilho animado, com prévia ao vivo e aplicação imediata no telão.
- Padrões para novos itens do roteiro: tempo das fotos na tela e o que fazer ao terminar.
- A versão instalada agora aparece em Configurações → Sobre.

### 0.1.0 — 09/10/2026

Primeira versão do Telon.

- Janela do operador e saída automática em tela cheia no segundo monitor (ou janela de teste, se não houver).
- Roteiro de vídeos e fotos: arrastar e soltar arquivos, reordenar e botão de excluir em cada item.
- Transição suave (crossfade) entre itens, com entrada e saída gradual do áudio.
- Fotos em pé com fundo desfocado; tempo de exibição ajustável.
- Ao terminar um item: avançar, repetir ou parar.
- Tela de descanso, tela preta e pausa.
- Atalhos de teclado para operar sem mouse.
- Aviso quando um arquivo não existe ou o formato não é suportado.
- Atualização automática: baixa em segundo plano e instala ao fechar o Telon.

---

Este repositório contém apenas os instaladores do Telon. © Attua
