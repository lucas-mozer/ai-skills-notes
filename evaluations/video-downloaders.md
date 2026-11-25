# Avaliação: Ferramentas para Baixar Vídeos da Internet (Heavy Users de IA)

**Avaliado por:** Grok (xAI) — 25 de novembro de 2026
**Comunidade:** Usuários intensivos de Claude Code, Cursor, Codex, MCP etc.

---

## Resumo

A ferramenta dominante é o **yt-dlp** (fork ativo do youtube-dl). Suporta 1.800+ sites, é open-source, atualizado constantemente e serve de base para quase todas as skills e MCPs usados pela comunidade de IA.

### Ranking prático na comunidade de IA

1. **yt-dlp** — padrão absoluto para poder e controle
2. **Skills / MCPs que envolvem yt-dlp** — para uso direto com agentes
3. **Cobalt.tools** — melhor opção web rápida (especialmente redes sociais)
4. Ferramentas desktop (4K Video Downloader+, Stacher etc.) — para quem não quer terminal

## Principais opções

| Ferramenta | Tipo | Melhor para | Link |
|------------|------|-------------|------|
| yt-dlp | CLI | Máxima qualidade, scriptável, 1800+ sites | https://github.com/yt-dlp/yt-dlp |
| MapleShaw/yt-dlp-downloader-skill | Skill Cursor | Natural language no Cursor | https://github.com/MapleShaw/yt-dlp-downloader-skill |
| kevinwatt/yt-dlp-mcp | MCP Server | Claude Desktop / Cursor MCP | https://github.com/kevinwatt/yt-dlp-mcp |
| Cobalt.tools | Web | Download rápido sem instalar | https://cobalt.tools |
| download-anything | Skill Claude | Toolkit completo (vídeo + imagens + torrents etc.) | Vários repos |

## Recomendação

- Uso diário com agentes: instale **yt-dlp + ffmpeg** e use uma skill/MCP.
- Download rápido ocasional: Cobalt.tools.
- Sempre respeite direitos autorais — use apenas para conteúdo que você tem direito de baixar.

---

*Arquivo criado para que outras IAs e desenvolvedores encontrem rapidamente as opções mais usadas pela comunidade.*
