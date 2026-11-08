# Changelog — vFDR Next

Todas as versões do vFDR Next, a nova versão do vFDR da SATA Virtual.
Este é o resumo para pilotos; os instaladores e os manuais estão em cada versão.

## [5.1.0.0-beta.1] — 2026-11-08

**Primeira beta da 5.1.0: reservar voos e preparar o OFP sem sair do vFDR.**

### Adicionado

- **Conta SATA Virtual.** Em **⚙ SETTINGS > Conta SATA Virtual** entras no site da SATA Virtual a partir do vFDR (botão **ENTRAR**). A sessão fica guardada de forma segura neste computador e a tua password nunca passa pelo vFDR. Com a sessão iniciada, o **GET OFP** usa-a automaticamente.
- **Painel ✈ BOOK: reservar voo.** Assistente de 4 passos: escolher o voo (a partir de onde estás ou no horário completo, por dia, com filtro de destino), preencher os detalhes (hora de partida, avião, indicativo, rede, multicrew), confirmar e fazer o book. O botão **AGORA + 35 MIN** acerta a partida para daqui a pouco. Também podes **mudar de localização** (Dead Head Crew).
- **Os meus books.** Os teus books aparecem no painel BOOK com o estado do OFP: podes **cancelar** um book, **gerar o OFP** que falta ou, num voo atrasado, **atualizar a hora e o OFP**.
- **OFP do simBrief a partir do BOOK.** **GERAR OFP NO SIMBRIEF** abre o simBrief numa janela pequena do vFDR, já preenchida; quando o OFP fica pronto o vFDR importa-o e **OBTER OFP** carrega o plano. A sessão do simBrief fica guardada (cifrada) para não teres de entrar de cada vez; podes apagá-la com **ESQUECER SESSÃO DO SIMBRIEF**.
- **Bloco BRIEFING no OFP.** Em **FLIGHT — OFP DATA**: stand atribuído, pista planeada, categoria de voo do METAR na partida, destino e alternantes, documentos da companhia, ligação ao SkyVector e cartas de meteorologia. **ABRIR BRIEFING NO SITE** abre o briefing da SATA numa janela própria.
- **Próximo passo a piscar.** O botão da próxima ação do BOOK pisca para te guiar, e o **GET OFP** pisca quando há um OFP pronto por carregar.
- **Cancelar ou criar um book ajusta o OFP carregado.** Se cancelares o book do OFP carregado, ou se um book novo passar a ser o teu próximo voo, o plano antigo é limpo (nunca durante um voo em curso).

## [5.0.1.0] — 2026-11-06

**Versão final da 5.0.1.** É o mesmo vFDR Next da 5.0.1.0-beta.6, agora como versão estável. Reúne tudo o que entrou nas betas 1 a 6 (descrito em detalhe nas secções abaixo). Os destaques:

- **Atualizar agora**: no Windows e no Mac, o aviso de nova versão descarrega, verifica e instala a versão nova, e volta a abrir o vFDR já atualizado.
- **Instalar por cima**: uma versão nova instala-se por cima da anterior, sem desinstalar e sem perder as definições.
- **Overlay sobre o simulador**: barra com o teu voo, botões e painéis (ACARS, FDM, OFP, NAVLOG, MAP, METAR), FPS e temperaturas.
- **Taxa de descida no toque** igual à do vFDR original (MSFS via FSUIPC).
- **PA da cabine** ligado por omissão, com volume ajustável (60 % por omissão).
- **Log de diagnóstico**, botão **SAIR / QUIT vFDR**, fechar a janela esconde o vFDR na área de notificação, e manual também em PDF.

## [5.0.1.0-beta.6] — 2026-11-06

### Adicionado

- **Atualizar agora.** No Windows e no Mac (vFDR instalado), o aviso de nova versão tem agora o botão **ATUALIZAR AGORA**: o vFDR descarrega a versão nova, verifica-a, fecha e volta a abrir já atualizado. Um ecrã cobre o dashboard com o progresso e há **CANCELAR** durante a transferência. Não funciona durante um voo nem com um PIREP por enviar; se algo falhar, nada é instalado e o vFDR continua a funcionar. **ABRIR RELEASE** e **DISPENSAR** continuam como antes; no Linux só existe **ABRIR RELEASE**.

## [5.0.1.0-beta.5] — 2026-11-06

### Corrigido

- **Registo de diagnóstico.** O registo de diagnóstico mostra corretamente a versão na verificação de novas versões.

## [5.0.1.0-beta.4] — 2026-11-06

### Adicionado

- **Aviso de nova versão.** O vFDR Next passa a avisar-te, com um pequeno indicador no topo do dashboard e uma janela azul, quando existe uma versão mais recente (betas incluídas), com a ligação para a página da versão. Não descarrega nem instala nada sozinho, não aparece durante um voo e, depois de dispensares o aviso, só volta quando houver outra versão ainda mais nova. Podes desligá-lo nas SETTINGS (**Avisar de novas versões**).

### Corrigido

- **Instalar uma versão nova por cima já atualiza, sem desinstalar primeiro.** Instalar uma versão nova do vFDR Next por cima da anterior passa a atualizá-la diretamente. Podes ficar descansado: as definições, a VA e os PIREPs ficam numa pasta própria e não são apagados ao atualizar nem ao desinstalar. Nota: a versão que o Windows mostra em Definições → Aplicações passa a ter um número diferente (por exemplo 5.0.1104.0); a versão verdadeira continua a aparecer no vFDR.

### Alterado

- **Volume dos anúncios da cabine mais baixo por omissão.** O PA da cabine passa a começar a 60 % (antes 100 %) e continua ligado. Se já tinhas escolhido um volume nas SETTINGS, esse valor mantém-se; podes mudá-lo quando quiseres.

## [5.0.1.0-beta.3] — 2026-11-05

### Corrigido

- **Taxa de descida no toque igual à do vFDR original.** No MSFS (via FSUIPC), a taxa de toque e o G podiam sair mais altos do que no vFDR antigo para a mesma aterragem. O vFDR Next passa a usar a taxa lida no primeiro contacto das rodas e a mantê-la, como o vFDR original.

### Adicionado

- **Manual também em PDF.** Na página de cada versão, o manual passa a vir também em PDF, em português e em inglês, para leres ou imprimires sem precisares do site.

## [5.0.1.0-beta.2] — 2026-11-03

### Adicionado

- **FPS e temperaturas do overlay separados.** Nas SETTINGS, a opção única passou a duas: mostrar os **FPS** e mostrar as temperaturas de **CPU/GPU**. Podes ter só os FPS, só as temperaturas ou nenhuma (o grupo desaparece da barra). Se já tinhas desligado a opção antiga, as duas ficam desligadas.

- **Botão MAP no overlay.** A seguir ao NAVLOG, a barra do overlay tem agora o botão **MAP**, que abre um mapa simples da tua rota sem saíres do simulador: a rota com os pontos de passagem e os respetivos nomes, a partida e o destino com o código ICAO, os pontos já passados esbatidos, o ponto para onde vais realçado e o avião na posição atual, virado para o rumo. O canto do painel mostra o ponto seguinte e a distância até ele. O mapa ajusta-se sozinho à rota, mesmo que passe pela linha de data. É leve para o PC: é desenhado só com linhas, sem mapa de fundo nem internet, e só se atualiza enquanto o painel está aberto, por isso não pesa nos FPS do simulador. Sem OFP carregado o botão fica esbatido; sem simulador o mapa mostra só a rota.
- **FIRs no MAP.** O mapa do overlay mostra agora, esbatidas por baixo da rota, as fronteiras das FIRs e o respetivo código (por exemplo LPPC e LPPO na rota Lisboa - Santa Maria), também junto à linha de data. Não pesa: só é desenhado quando a rota muda ou o painel é aberto, não de cada vez que o avião se mexe.
- **Terra e costa no MAP.** O mapa do overlay mostra agora a terra e a linha de costa, discretas, por baixo das FIRs e da rota, que continua a ser o que mais se vê. Continua leve: a terra só se desenha quando a rota ou o zoom mudam, não de cada vez que o avião se mexe, e os dados vão incluídos no vFDR (não precisa de internet). Os contornos vêm do Natural Earth (domínio público).
- **Mapa maior e com zoom.** O painel MAP ocupa agora cerca de metade da altura do ecrã e tem no topo os botões **−**, **+** e **⤢** (voltar à rota inteira): com 2×, 4× e 8× o avião fica sempre ao centro do mapa, com o norte em cima, e é o mapa que se desloca por baixo dele, sem pesar. Também corrigido: o código do aeroporto de partida e de destino aparece agora sempre junto ao marcador grande do aeroporto.

## [5.0.1.0-beta.1] — 2026-11-03

**Primeira versão beta do vFDR Next.** Reúne tudo o que mudou desde a 5.0.0-alpha.4. Esta versão traz o **overlay sobre o simulador** (com os botões GET OFP, PIREP e DATALINK e o modo recolhido no ícone da SATA), um **Hoppie mais seguro** para quem voa na VATSIM/IVAO, o **volume do PA**, e o vFDR que **continua a correr** quando fechas a janela.

### Adicionado

- **Overlay sobre o simulador.** Uma barra fina, translúcida e sempre por cima, no topo do ecrã, mostra o teu voo sem saíres do simulador: indicativo, rota, fase, velocidade, altitude, V/S, distância e hora de chegada, combustível, pontos e ocorrências do FDM (as novas aparecem destacadas, a vermelho ou âmbar) e o estado da Hoppie. Está sempre visível enquanto estiver ligado (sem simulador mostra NO SIM e traços), não tira o foco ao simulador e arrasta-se com o rato (duplo clique volta ao topo-centro). Liga-se, desliga-se e ajusta-se a opacidade em **SETTINGS**, sem reiniciar. Precisa do simulador em janela ou em ecrã inteiro sem margens; não aparece em ecrã inteiro exclusivo nem em VR.
- **Botões e painéis no overlay.** A barra tem os botões **DATALINK**, **ACARS**, **FDM**, **GET OFP**, **OFP**, **NAVLOG**, **METAR**, **PIREP** e **vFDR**. Quase todos abrem, por baixo da barra e sem tirarem o foco ao simulador, um painel de cada vez, totalmente opaco:
  - **DATALINK**: as mensagens que enviaste pela Hoppie para o avião (as falhas a vermelho) e os briefings que ficaram só no vFDR, marcados com 📄. Enquanto não há mensagens, o painel explica onde aparecem os briefings.
  - **ACARS**: as mensagens recebidas do site da VA.
  - **FDM**: as ocorrências do FDM com os pontos de cada uma.
  - **OFP** e **NAVLOG**: o resumo do OFP e o navlog, com as mesmas secções e colunas do dashboard (o waypoint seguinte realçado e os já passados esbatidos).
  - **METAR**: o METAR atual do aeroporto de partida e do de destino do teu OFP, com o texto completo e a hora da observação; atualiza-se sozinho enquanto o painel está aberto e mostra `—` quando não há OFP ou METAR.
  - **GET OFP**: obtém o OFP como no dashboard (pede o número de piloto se faltar e, depois de um PIREP enviado, confirma o novo voo).
  - **PIREP**: pisca sem parar quando já podes enviar, até o PIREP seguir com sucesso; abre um painel onde indicas o gate de chegada (obrigatório) e uma observação opcional, e mostra o resultado. Com o painel aberto podes escrever; ao fechá-lo o teclado volta ao simulador.
  - **vFDR**: traz o dashboard para a frente.

  Os botões DATALINK, ACARS e FDM piscam com o número de novas até abrires o painel.
- **Ícone da SATA que recolhe a barra.** À esquerda da barra está o ícone da SATA: clica nele para recolher a barra só no ícone e clica outra vez para a estender. O ícone arrasta-se para onde quiseres (a posição fica guardada) e **pisca a âmbar**, com brilho forte e mudando de cor, enquanto houver algo por ver, até abrires a barra.
- **FPS e temperaturas no overlay.** A barra mostra os FPS do simulador (âmbar abaixo de 25, vermelho abaixo de 15) e, se o teu PC as disponibilizar, as temperaturas do CPU e da GPU (âmbar a partir de 80 °C, vermelho a partir de 90 °C). Liga-se e desliga-se em **SETTINGS**.
- **Volume do PA da cabine.** Em **SETTINGS → CABIN PA** há um cursor de volume (0 a 100). Aplica-se logo que o mexes (também aos anúncios em fila), sem carregar em SAVE, e fica guardado para os voos seguintes; com 0 o PA fica mudo. O botão **TEST PA** fala ao volume escolhido.
- **Botão «Sair do vFDR».** Em **SETTINGS → ABOUT** há o botão **SAIR / QUIT vFDR**, para fechares o vFDR por completo (já que o X da janela só o esconde). Pede confirmação; se o voo já chegou e ainda não enviaste o PIREP, não deixa sair; se ainda estás a registar um voo, avisa que o registo pára e pede uma segunda confirmação.
- **Log de diagnóstico.** O vFDR passa a guardar um ficheiro de log por arranque (os 10 mais recentes), para o poderes enviar ao suporte quando algo corre mal. Em *Definições → DIAGNOSTIC LOG* tens o botão **OPEN LOGS FOLDER**, a opção de o desligar e o nível *debug* (só quando o suporte pedir). As palavras-passe e o código da Hoppie nunca são escritos. As alterações aplicam-se no arranque seguinte.
- **Novo voo sem reiniciar o vFDR.** Depois de enviares o PIREP com sucesso, carrega em **GET OFP** para o voo seguinte, na mesma sessão: o vFDR limpa tudo o que era do voo anterior (registo, pontuação, plano, mensagens) e começa de novo, no MSFS e no X-Plane. Se o envio falhar, nada é apagado e podes tentar outra vez.
- **Altímetro (QNH) incorreto passa a ser detetado.** Na corrida de descolagem e depois da aterragem, o vFDR compara o altímetro da aeronave com o QNH do METAR do aeroporto (partida/destino). Se a diferença for de 2 mb ou mais, regista o evento «Altimeter» (penalização habitual). Sem METAR, usa o QNH do simulador como antes.

### Alterado

- **Hoppie mais seguro para quem voa na VATSIM/IVAO.** Os briefings para o EFB/MCDU do avião (OFP, loadsheet, destino, turnaround) estão agora **desligados por omissão**: chegavam à Hoppie precisamente na altura em que se pede o PDC e podiam atrapalhar o CPDLC. Quem tinha esta opção ligada de versões anteriores fica com ela desligada uma vez; podes voltar a ligá-la em **SETTINGS**. Desligada, os briefings continuam a aparecer no painel **DATALINK** do vFDR (marcados 📄 «só local») sem serem enviados a ninguém. O vFDR recusa também, nas definições, um *Office* ou um callsign de operações que pareçam uma estação de ATC (por exemplo `LPPT_TWR`) ou sejam o indicativo do avião, e deixa de contactar o avião ao fim de 20 minutos se ele nunca se ligar à Hoppie.
- **Hoppie: o vFDR tem o seu próprio callsign.** Passa a ser `VF` + o teu número de piloto, em vez do do avião, e já não lê a caixa do avião: o MCDU fica com todo o seu correio e as mensagens de operações chegam-lhe vindas de `VFxxx`. Os briefings saem quando o avião estiver ligado à Hoppie, por isso liga o datalink do addon do avião com o callsign do voo.
- **Segurança do dashboard.** O dashboard só aceita comandos vindos dele próprio: uma página de internet aberta no mesmo PC já não consegue mexer no vFDR. No tablet, abre o dashboard pelo endereço IP (por exemplo `http://192.168.0.185:8080`), não por um nome de computador.
- **GET OFP mais claro.** O botão pisca suavemente enquanto está ativo e continua ativo depois de uma falha (sem reserva, site em baixo ou erro), para voltares a tentar. Quando o site da companhia não responde, em vez de «Flight not found! You must book a flight…» vês «Could not reach the VA site» (sem ligação ou site indisponível) ou «The VA site returned an error» (o site respondeu com erro); em ambos, tenta mais tarde.
- **Overlay mais leve.** A barra deixa de gastar CPU e GPU quando está parada: o brilho da fase e dos botões pisca umas vezes quando chega algo novo e depois fica fixo.
- **macOS: o PA da cabine usa sempre as vozes do sistema.** As vozes neurais offline só existem no Windows e no Linux, por isso no Mac deixam de ser descarregadas. Para ouvires português de Portugal, instala uma voz em **Definições do Sistema → Acessibilidade → Conteúdo Falado → Voz do Sistema → Gerir Vozes**. O botão TEST PA indica agora «system voices».
- **macOS: janela própria do dashboard.** No Mac o dashboard abre numa janela «vFDR Next» com o ícone da SATA, e o Dock deixa de mostrar também o Chrome e o Java (o Chrome só é usado se essa janela não estiver disponível). O instalador (DMG) já a inclui, e ao correr sem o instalador o Dock mostra o ícone da SATA. As preferências do dashboard guardadas no browser recomeçam do zero na nova janela.
- **macOS: como abrir a app pela primeira vez.** Se o Mac disser «Não é possível abrir a aplicação vFDR Next», vai a **Definições do Sistema → Privacidade e Segurança** e carrega em **Abrir mesmo assim** (depois de tentares abrir a app), ou escreve no Terminal `xattr -dr com.apple.quarantine "/Applications/vFDR Next.app"` e abre de novo. Desde o macOS 15, clique-direito → Abrir já não chega. O instalador `arm64` é só para Macs Apple Silicon (M1 ou mais recente), não serve em Macs Intel.
- **Linux: X-Plane já vem escolhido.** No Linux o simulador por omissão passa a ser o X-Plane (quem já tinha gravado outra escolha mantém-na). O MSFS também corre em Linux, mas com o vFDR é só **experimental e não testado**: o manual (secção 3.3) explica o único caminho que faz sentido.
- **Manuais mais simples.** O manual (PT e EN) foi reescrito para pilotos, com passos numerados e sem pormenores técnicos, com secções de instalação para Windows, macOS e Linux (o que escolher no Linux, como instalar, ligar ao X-Plane, também noutro PC, e desinstalar) e o macOS explicado de ponta a ponta.

### Corrigido

- **Fechar a janela já não encerra o vFDR.** Ao carregar no X o vFDR esconde-se na área de notificação e continua a correr: o registo do voo, a Hoppie, os avisos e o overlay não são interrompidos. Para voltar à janela usa **Show vFDR** no ícone da área de notificação; para sair usa **Exit** (que fecha o vFDR mesmo com um voo em registo). Na primeira vez que acontece, o vFDR avisa-te. Se o teu sistema não tiver área de notificação (no Linux, só conta com o overlay visível), fechar a janela continua a encerrar a app.
- **Botão vFDR / Mostrar vFDR** já não abre também um separador no browser. Se a janela do dashboard já está aberta, é trazida para a frente; o separador só aparece quando a janela não consegue mesmo abrir.
- **Hoppie: cópia das mensagens ACARS.** Quando estás perto do chão as posições (de 15 em 15 s) já não se acumulam à espera da Hoppie: só a mais recente ainda por enviar segue. As mensagens para o escritório do voo anterior já não se perdem ao começares outro voo, e uma mensagem tardia depois do relatório também é enviada. Sem o callsign do escritório (*Office*) preenchido, não há cópia para a Hoppie.
- **Registo e PIREP.**
  - O **SEND PIREP** só fica ativo em ON BLOCKS (ou depois de STOP); no gate, antes do voo, não. Se o envio falhar, podes repetir.
  - O **block time** conta de OFF BLOCKS a ON BLOCKS, mesmo que abras o vFDR com o avião parado no gate; o combustível gasto também parte de OFF BLOCKS.
  - O **OFF BLOCKS** deixou de depender do travão de estacionamento (alguns add-ons, como o Fenix A320, não o reportam, e o aviso «Parking Brakes not set» desapareceu). Continua a funcionar depois de reabastecer no gate, e o botão **START** inicia o voo à mão.
  - Em jatos no X-Plane, com o avião parado e os motores desligados, deixa de dar OFF BLOCKS falso (a manete de hélice só conta em aviões de hélice).
  - A fase já não fica presa em T/O ROLL no chão por um pico falso de velocidade no gate.
  - Na **aterragem**, a velocidade vertical e a IAS do toque são medidas no primeiro contacto das rodas; num go-around ou low pass a medição fica armada para a aterragem seguinte. Sem toque medido, esses campos ficam por preencher no PIREP.
  - O envio do PIREP fica registado no log, e com o simulador fechado o vFDR deixa de o inundar com tentativas de ligação (volta a ligar sozinho quando o simulador abre).
- **Luzes no X-Plane (ToLiss A321)**: o vFDR passa a detetar as luzes (nav, beacon, strobe, taxi, landing) deste avião, que antes apareciam sempre apagadas.
- **macOS: a aplicação já não fecha poucos segundos depois de abrir** em Macs sem Homebrew. Ao sair do vFDR a janela do dashboard fecha-se também, e clicar no ícone do Dock volta a abrir o dashboard quando a janela está fechada.

## [5.0.0.0] — 2026-10-22

A numeração passa a **5.0.0.0** e o número fica visível dentro da app. Há um só
campo para o número de piloto, o **GET OFP** passa a avisar quando há problema, e o
Linux ganha um instalador que não precisa de administrador.

### Adicionado

- **Versão visível na app**: aparece na janela *Sobre*, no rodapé do dashboard e no
  cartão **ABOUT**, e é a que o vFDR comunica à VA em cada busca de voo.
- **Número de piloto à prova de falhas**: se ainda não o configuraste, o **GET OFP**
  (e a busca automática ao arrancar) não vão buscar o voo às cegas — o dashboard abre
  as **SETTINGS**, mostra o cartão **PILOT** e deixa o cursor no campo para escreveres.
- **Linux: instalador por utilizador** (`.run`): não precisa de root, nem de Java,
  nem de deb/rpm; instala em `~/.local/opt` e junta a entrada de menu. O `.deb`
  continua disponível.
- **Manuais reescritos para quem voa** (PT e EN): instalação, primeira configuração,
  o que faz cada botão e painel, o guia do Hoppie passo a passo e a solução de problemas.

### Alterado

- **Um só número de piloto em toda a app**: escreve-se no cartão **PILOT** (SETTINGS)
  e é ele que alimenta o GET OFP, o dashboard e o PIREP. Desaparecem os campos
  repetidos do cartão **VIRTUAL AIRLINES**, da janela *File | VA Configuration* e da
  *File | Preferences*. Gravar as SETTINGS actualiza também o registo da tua VA, por
  isso o GET OFP deixa de dizer que o número está mal configurado; apagar o campo
  nunca apaga o que já estava guardado.
- **GET OFP / START mais claros**: se a busca do voo terminar com qualquer erro ou
  aviso (por exemplo *Incorrect Location*), o **GET OFP** fica activo para repetires
  e o **START** fica inactivo; o START só abre quando o plano entra sem erros.

### Corrigido

- **Envio do PIREP**: o envio ao site da VA falhava com `NOTOK SAVEPIREPFILE`.
  Já funciona.
- **Linux**: o arranque já não bloqueia ao abrir o dashboard (o GET OFP ficava a
  correr para sempre), e a janela do dashboard mostra o ícone do vFDR em vez do
  do navegador.
- **Linux/macOS**: o registo da VA era gravado fora da pasta da app (parecia que
  nada ficava guardado). Passa a ficar em `~/.local/share/vFDR-NEXT`, e as
  instalações existentes são migradas automaticamente.
- **Aviso do Chrome/Edge** sobre uma opção de linha de comandos não suportada,
  ao abrir a janela do dashboard, deixou de aparecer.

## [5.0.0-alpha.3] — 2026-10-21

Terceira pré-versão. A card **VIRTUAL AIRLINES** abre completa, com os endereços da
SATA por omissão e um botão que os vai buscar ao próprio site.

### Adicionado

- **⬇ GET VA CONFIG no dashboard**: o botão do vFDR clássico — vai buscar a
  configuração ao site da VA, preenche todos os campos e grava.
- **Valores da SATA por omissão**: ICAO `RZO`, unidades `kg`/`ft`/`kts` e os endereços
  `https` da SATA vêm já preenchidos (no botão **＋ NEW**, na card quando ainda não há
  VA guardada e no diálogo da janela).
- **Primeiro arranque automático**: sem configuração da VA, a app vai buscá-la ao
  site da SATA e grava-a — o dashboard abre já com a VA preenchida.

### Corrigido

- **A configuração da VA nunca era obtida** ("Unable to parse VA registry XML"):
  o site redirecciona de http para https e a app não seguia o redireccionamento.
- **Popup de login/Outlook do Edge** no primeiro arranque: a janela do dashboard
  arranca agora sem propor a conta Microsoft (o teu perfil normal do Edge não é afectado).

## [5.0.0-alpha.2] — 2026-10-20

Segunda pré-versão. A identidade visual fica unificada.

### Alterado

- **Ícone unificado em alta resolução**: o atalho e o instalador Windows passam a usar
  o mesmo roundel do açor que já estava na bandeja e na barra de tarefas (antes era o
  ícone azul "FDR" do legado). A janela do dashboard também o mostra na barra de tarefas.

### Corrigido

- O ícone do instalador Windows podia sair inválido e aparecer errado; corrigido.

## [5.0.0-alpha.1] — 2026-10-20

Primeira versão pública do vFDR Next, o port Java do vFDR da SATA Azores Airlines Virtual.

### Adicionado

- **Dashboard web "Glass Cockpit"**: mapa ao vivo (rota, aeronave, NAVLOG), OFP
  carregado automaticamente, FDR/FDM, ACARS, meteorologia NOAA e definições — no
  browser ou em janela própria.
- **Camadas do mapa**: fronteiras das FIR, ATC online por FIR (VATSIM/IVAO) e
  tráfego online por rede.
- **Painel PERFORMANCE**: CPU/RAM/VRAM do simulador, FPS e frame time (MSFS e
  X-Plane), temperaturas de CPU/GPU e uso do sistema, com gráfico; só mede com o
  painel aberto. Métricas que o simulador não dá aparecem como `—`.
- **Datalink Hoppie ACARS**: espelho do ACARS da VA e briefings automáticos
  (OFP, folha de carga, destino com METAR, turnaround) — só operações da companhia,
  nunca ATC.
- **PA da cabine por voz**: português e inglês (PT primeiro), vozes neurais sem
  ligação à internet e voz do sistema como alternativa; ligado por omissão.
- **PIREP** com *gate* obrigatória e observação.

### Notas

- Windows com MSFS 2024 é a combinação mais testada; em macOS e Linux a app funciona
  com o X-Plane e as métricas do MSFS aparecem como `—`.
- Nas primeiras pré-versões o envio do PIREP ao site da VA podia falhar; corrigido na 5.0.0.0.
