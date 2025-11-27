# Falar313 - Mini Estúdio de Síntese de Voz

**Falar313** é um projeto em Python que permite gerar áudio de narração a partir de texto, aplicando efeitos de reverb, echo, velocidade, graves e agudos. Possui interface gráfica com **Tkinter** e permite gerar tanto arquivos `.mp3` quanto `.wav` com efeitos.

---

## 💻 Funcionalidades
- Gerar voz a partir de texto usando vozes em português (pt-BR e pt-PT).  
- Aplicar efeitos de áudio: Reverb, Echo, Speed, Bass, Treble.  
- Visualizar lista de arquivos gerados com duração.  
- Tocar arquivos diretamente na interface.  
- Interface amigável usando Tkinter.

---

## ⚙️ Requisitos
- Python 3.13  
- Bibliotecas Python:
  - `edge_tts`
  - `asyncio`
  - `tkinter` (geralmente já incluso no Python)
- FFmpeg (para conversão e aplicação de efeitos)
- Windows ou Linux (compatível, mas testes foram feitos no Windows)

---

## 📝 Como usar

### 1. Rodando o script Python
1. Clone ou baixe o repositório:
```bash
git clone https://github.com/aazmgraphics/falar313.git
