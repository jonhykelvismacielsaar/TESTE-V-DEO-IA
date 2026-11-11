# GUIA DE PRODUÇÃO — Episódio 1 · Seedance 1.5 + CapCut

Este guia é o passo a passo para transformar os 20 frames em um episódio de **60 segundos cravados**.

---

## 1. Configurações no Seedance 1.5 (para todos os 20 clipes)

| Parâmetro | Valor | Por quê |
|---|---|---|
| **Modo** | **Imagem para vídeo (Image-to-Video)** | Garante que o frame aprovado seja o primeiro quadro — é o que mantém o rosto e o figurino. |
| **Primeiro frame** | A imagem do `seqXX` correspondente | Nunca gere por texto puro se a consistência importa. |
| **Duração** | **5 segundos** em **todos** os clipes | As transições também são geradas em 5s e cortadas em 1s no CapCut. |
| **Proporção** | **9:16** (vertical) | Reels / TikTok / Shorts. |
| **Resolução** | **1080p** (se a conta permitir), senão 720p | O CapCut aguenta 720p, mas 1080p dá margem para o zoom de 1s. |
| **Áudio** | **Ativado** (áudio nativo / fala PT-BR) | É o diferencial do 1.5: lipsync + som no mesmo passo. |
| **Música** | **Desativada** | Trilha entra só no CapCut. Ambiência e SFX ficam no clipe. |
| **Movimento** | **Automático / natural** | Não force "câmera fixa" nos frames de ação. |

### Prompt negativo (cole no campo *negative prompt*, se houver)
```
subtitles, captions, text, watermark, logo, extra fingers, deformed hands,
distorted face, extra characters, cartoon, anime, low resolution, blurry,
oversaturated, music, background song
```

> Se a ferramenta não tiver campo de negativo, o final dos prompts já contém
> `no subtitles, no on-screen text, no watermark` — resolve 90% dos casos.

---

## 2. Ordem de produção (não inverta)

```
1. Gerar as 20 IMAGENS  →  aprovar as 3 âncoras (Nara, Luan, Casa Estrela)
2. Gerar os 10 VÍDEOS de cena (F01–F10)      → 5s cada  = 50s
3. Gerar as 10 VÍDEOS de transição (T01–T10) → 5s cada  = 50s (corta em 10s)
4. Montar no CapCut e cortar as transições em 1s
5. Sound design + trilha + cartelas + legenda queimada
```

**Regra de ouro da consistência:** antes de gerar cada vídeo, jogue no Seedance a
imagem aprovada do personagem como **referência de sujeito** (além do primeiro frame).
Nos prompts já está escrito *"Keep her scar, earrings and raincoat identical"* — isso
funciona junto com a referência visual.

---

## 3. Montagem no CapCut (timeline exata)

| Clip | Duração | Entra em | Termina em |
|---|---|---|---|
| F01 Cena | 5s | 00:00.0 | 00:05.0 |
| T01 Transição | **1s** | 00:05.0 | 00:06.0 |
| F02 Cena | 5s | 00:06.0 | 00:11.0 |
| T02 Transição | **1s** | 00:11.0 | 00:12.0 |
| F03 Cena | 5s | 00:12.0 | 00:17.0 |
| T03 Transição | **1s** | 00:17.0 | 00:18.0 |
| F04 Cena | 5s | 00:18.0 | 00:23.0 |
| T04 Transição | **1s** | 00:23.0 | 00:24.0 |
| F05 Cena | 5s | 00:24.0 | 00:29.0 |
| T05 Transição | **1s** | 00:29.0 | 00:30.0 |
| F06 Cena | 5s | 00:30.0 | 00:35.0 |
| T06 Transição | **1s** | 00:35.0 | 00:36.0 |
| F07 Cena | 5s | 00:36.0 | 00:41.0 |
| T07 Transição | **1s** | 00:41.0 | 00:42.0 |
| F08 Cena | 5s | 00:42.0 | 00:47.0 |
| T08 Transição | **1s** | 00:47.0 | 00:48.0 |
| F09 Cena | 5s | 00:48.0 | 00:53.0 |
| T09 Transição | **1s** | 00:53.0 | 00:54.0 |
| F10 Cena | 5s | 00:54.0 | 00:59.0 |
| T10 Transição | **1s** | 00:59.0 | 01:00.0 |

**TOTAL: 60,0 segundos.**

### Como cortar as transições em 1 segundo sem perder a ação

Os prompts de transição já foram escritos com a **ação inteira acontecendo entre 0,0s e 1,0s**
(ex.: *"From 0.0 s to 1.0 s: the coin spins and flashes to white-gold"*). Os 4 segundos restantes
são só movimento contínuo de poeira, luz ou moedas.

No CapCut:

1. Arraste o clipe de transição para a timeline (ele vem com 5s).
2. Coloque o **playhead em 1,0s** e use **Dividir** (`Ctrl+B` / `⌘B`).
3. Apague a segunda parte (ou deixe no *media pool* para reaproveitar como B-roll).
4. Se quiser ainda mais impacto, aplique **Velocidade → Curva personalizada** e
   deixe a aceleração no fim do 1s.

> **Dica:** as transições também funcionam como *flash* de 0,3s se você cortar ainda mais.
> Teste 1s (padrão) e 0,5s (versão agressiva para TikTok).

---

## 4. Sound design (o que faz parecer cinema)

| Momento | Efeito |
|---|---|
| F01 | Chuva forte + trovão distante + zumbido do letreiro |
| T01–T10 | **Todo "flash" dourado pede um `whoosh` + `riser` curto** (0,8s) |
| F05 (a aposta) | Riser subindo até o último segundo + impacto grave no corte |
| F06 (a reviravolta) | **Cortar toda a ambiência** — deixar só o silêncio e a respiração |
| F08 (os fantasmas) | Sussurros em camada, reverb longo, sem música |
| F10 (cliffhanger) | **Batida de sub-bass + silêncio seco** no corte final |

**Trilha:** uma faixa só, em *crescendo* constante. Sugestão: cordas graves + piano
mínimo, ~60 BPM, entrando baixinho em F02 e explodindo em F05. Nos episódios seguintes,
mantenha o **mesmo tema** — é assinatura de série.

**Regra de ouro:** nunca deixe música e fala competirem. Em F06 e F10, deixe a fala nua.

---

## 5. Cartelas de texto (CapCut)

| Tempo | Texto | Estilo |
|---|---|---|
| 00:00.3 → 00:02.0 | **ELE ME DEIXOU UMA CASA.** | Serifada, branca, tracking largo |
| 00:29.3 → 00:30.0 | **NÃO É OURO.** | Idem, maior |
| 00:59.2 → 01:00.0 | **O PREÇO DA SORTE** | Cartela final + "Ep. 2 — A Aposta de Luan" |

Sempre **4 a 6 letras por linha** no vertical, centralizado no terço superior.
Deixe 120px de margem no topo e embaixo (a UI do TikTok cobre).

---

## 6. Cor e acabamento

- **LUT:** procure uma que puxe **sombras para o azul-petróleo e altas luzes para o dourado**.
  Ajuste manual equivalente: *Temperatura +8, Sombras +azul, Realce +dourado, Saturação -5*.
- **Grain:** 35mm leve (o CapCut tem "Film Grain"). Intensidade 15–25.
- **Vignette:** leve, sempre. A casa precisa parecer fechada.
- **Transições do CapCut:** use **"Nada" (corte seco)** em tudo. O corte seco é o que
  dá o ritmo de micro-drama. Nada de *dissolve* — a não ser em F05 → T05.

---

## 7. Checklist antes de exportar

- [ ] Duração exata: **60,0s** (confira com o contador do CapCut)
- [ ] Todas as transições com 1s
- [ ] Nara com o mesmo casaco amarelo em F01–F06 e o mesmo vestido vermelho em F07–F10
- [ ] Luan com a mesma mecha branca em todas as cenas
- [ ] Nenhum texto gerado pela IA dentro do vídeo (só as cartelas do CapCut)
- [ ] Falas PT-BR sincronizadas (teste em 0,5x)
- [ ] Exportar **1080×1920, 30fps, H.264, 12 Mbps**
