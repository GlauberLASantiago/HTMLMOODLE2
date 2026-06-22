# 🎵 Player de Partitura — MusicXML para Moodle/Web

Ferramenta interativa para **visualizar e tocar partituras** em formato MusicXML diretamente no navegador, com integração ao **Moodle** via exportação de HTML embutido.

Desenvolvido pelo professor **Glauber Santiago** — DAC/UFSCar  
🔗 [servidores.ufscar.br/glauber](https://servidores.ufscar.br/glauber/) | [sites.google.com/view/glauberia](https://sites.google.com/view/glauberia)

---

## ✨ Funcionalidades

- 📂 **Carregamento de arquivos** `.xml` / `.musicxml`
- 🎼 **Renderização da partitura** com a biblioteca [OpenSheetMusicDisplay (OSMD)](https://opensheetmusicdisplay.org/)
- ▶️ **Reprodução de áudio** com cursor animado sincronizado (via [Soundfont Player](https://github.com/danigb/soundfont-player))
- 🎹 **Seleção de timbre** por instrumento (General MIDI)
- 🎚️ **Controles de playback**: Play / Pause / Stop
- 🕐 **Ajuste de andamento** (BPM)
- 🔔 **Metrônomo** opcional durante a reprodução
- 🌊 **Reverb** ajustável
- 🎵 **Transposição** e **deslocamento de oitava**
- 🎛️ **Painel por partes**: mudo, solo e timbre individual por instrumento
- 📐 **Layout configurável**: número de compassos por sistema
- 📋 **Copiar HTML** — gera o player completo para colar no Moodle
- ⬇️ **Baixar HTML** — salva o player como arquivo `.html` independente

---

## 🚀 Como usar

### No navegador (modo local)

1. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge).
2. Clique em **"Carregar MusicXML"** e selecione seu arquivo `.xml` ou `.musicxml`.
3. Use os controles para ajustar BPM, timbre, transposição etc.
4. Clique em **▶ Play** para ouvir a partitura com cursor animado.

### Integrando ao Moodle

| Passo | Ação |
|-------|------|
| 1 | **Exportar XML** — No MuseScore (ou similar), exporte a partitura em formato MusicXML. |
| 2 | **Carregar & Ajustar** — Carregue o arquivo nesta ferramenta e configure conforme desejado. |
| 3 | **Copiar HTML** — Clique em "Copiar HTML" para copiar o player para a área de transferência. |
| 4 | **Colar no Moodle** — No editor do Moodle, clique no botão `< / >` (HTML) e cole o código. |

---

## 🛠️ Tecnologias

| Biblioteca | Versão | Finalidade |
|---|---|---|
| [OpenSheetMusicDisplay](https://github.com/opensheetmusicdisplay/opensheetmusicdisplay) | 1.9.7 | Renderização de partituras MusicXML |
| [Soundfont Player](https://github.com/danigb/soundfont-player) | 0.12.0 | Síntese de áudio via soundfonts MIDI |

Não requer instalação, servidor ou dependências extras — é um único arquivo `index.html`.

---

## 📄 Licença

Uso livre para fins educacionais. Para outros usos, entre em contato com o autor.
