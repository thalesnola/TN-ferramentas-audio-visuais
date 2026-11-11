Feito por cópia de repo privado ferramentas-audio-visuais na versão 3e90a21 de TN em 11/2026.

---

# Ferramentas audiovisuais

Ferramentas, configurações de referência e métodos de produção audiovisual. Somente código e documentação: sem dados de caso, credenciais, pesos de modelos, vozes, mídias ou arquivos de produção.

| Pasta | Conteúdo |
|---|---|
| [codex/](codex/README.md) | Integrações MCP, plugins e skills configurados no Codex Windows |
| [artcraft/](artcraft/README.md) | Sete aplicativos de imagem, vetor, composição, PDF, foto, vídeo e diagramação |
| [voicestudio/](voicestudio/README.md) | Backend local CUDA, OmniVoice offline e inicialização automática pelo MCP |
| [wangp/](wangp/INSTALL.md) | WanGP, lançador e liberação de GPU; MCP 2.1 incluído no exemplo Codex |
| [video-codigo/](video-codigo/SKILL.md) | Material original de vídeo como código: HTML → MP4 via Playwright e FFmpeg |
| [generativo/](generativo/README.md) | Google Flow (Veo, Nano Banana), Omni e ChatGPT Images: roteamento, custos e armadilhas medidas |
| [skills-animacao/](skills-animacao/README.md) | Duas skills próprias para dez estilos visuais e quatro skills de terceiros auditadas, com receitas de instalação |
| [hypit/](hypit/README.md) | Skill de direção de vídeo com mídia gerada (hypit-ai), auditada, com ressalvas de sigilo e consentimento |
| [rhubarb-lipsync/](rhubarb-lipsync/README.md) | Skill própria de lip sync (Rhubarb auditado, teste em português, curvas de blendshape 3D) |
| [sons/](sons/README.md) | `openverse-sfx` (efeitos e música CC com créditos) e `earshot` (medir e criticar áudio), de terceiros, auditadas, corrigidas e instaladas |
| [docs/inventario.md](docs/inventario.md) | Versões verificadas, evidências e limites dos testes em 06/11/2026 |

Os exemplos usam `C:/Tools/audio-visual` como raiz ilustrativa. Substituir pelos caminhos reais; não executar instaladores macOS no Windows. Os binários e modelos são obtidos nas fontes originais, fora deste repositório.

O material histórico de `video-codigo/` foi escrito para Claude Code e permanece preservado. Sua referência também é versionada em `claude-config`; inspiração: yihui-dev/awesome-opus5-5-videos. As novas instruções de Codex estão separadas em `codex/`.

