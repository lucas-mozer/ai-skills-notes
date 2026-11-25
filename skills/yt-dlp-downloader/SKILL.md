---
name: yt-dlp-downloader
description: Download videos, audio, and subtitles from 1800+ sites using yt-dlp. Use when the user provides a video URL and wants to download it, extract audio, get subtitles, or archive media.
---

# yt-dlp Downloader Skill

Baixa vídeos, áudio e legendas de YouTube, X/Twitter, TikTok, Instagram, Bilibili e mais de 1800 sites usando yt-dlp.

## Pré-requisitos

- `yt-dlp` instalado (`pip install -U yt-dlp` ou `brew install yt-dlp`)
- `ffmpeg` instalado (para merge e extração de áudio)

## Uso típico

Quando o usuário pedir para baixar um vídeo:

1. Confirme que yt-dlp e ffmpeg estão disponíveis.
2. Execute o download com as opções apropriadas.

### Comandos recomendados

```bash
# Melhor qualidade (padrão)
yt-dlp "URL" -o "~/Downloads/%(title)s.%(ext)s"

# Até 1080p
yt-dlp -f "bv*[height<=1080]+ba/b" "URL"

# Só áudio em MP3
yt-dlp -x --audio-format mp3 "URL"

# Com legendas
yt-dlp --write-subs --sub-langs "pt,en" "URL"

# Contornar alguns bloqueios (cookies do browser)
yt-dlp --cookies-from-browser chrome "URL"
```

## Notas importantes

- Respeite direitos autorais. Baixe apenas conteúdo que você tem direito.
- Para YouTube com restrições, cookies do browser costumam resolver.
- Use `-P` ou `-o` para controlar a pasta de destino.

## Quando usar este skill

- "Baixa esse vídeo"
- "Extrai o áudio desse link"
- "Baixa em 720p com legendas"
- Qualquer URL de vídeo de site suportado pelo yt-dlp
