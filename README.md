# Packet Rescue Network Quest

Network mission game where teams move a packet through ARP, DNS, TCP, HTTP, latency and simulated failures.

> Educational project inspired by EETEPA Vilhena Alves. It is not an official institutional system and does not use real student data.

## Overview

**Code:** L-02  
**Discipline focus:** Computer Networks and Web Technologies  
**Format:** Teacher-led classroom web game  
**Suggested duration:** 25 to 35 minutes  
**Public demo:** https://albertomateus9.github.io/packet-rescue-network-quest/

This project turns a technical lesson into a guided mission. The teacher creates fictional teams, starts a timer, reveals mission phases, scores evidence and exports a classroom report.

## Classroom Flow

- **Find The Local Link ID:** Explain why local link resolution happens before the first frame is sent.
- **Decode The Destination:** Order the DNS, TCP, and HTTP steps correctly.
- **Rescue From Congestion:** Choose whether the likely cause is DNS, link congestion, or server failure using the clues.

## Competencies

- network reasoning
- protocol sequencing
- incident diagnosis
- technical vocabulary

## Run Locally

Open `index.html` directly or serve the folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Data Policy

- Uses synthetic missions and fictional teams only.
- Stores state only in browser `localStorage`.
- Has no login, backend, external API or real student record.

---

# Packet Rescue Network Quest

Network mission game where teams move a packet through ARP, DNS, TCP, HTTP, latency and simulated failures.

> Projeto educacional inspirado na EETEPA Vilhena Alves. Nao e sistema oficial institucional e nao usa dados reais de estudantes.

## Visao Geral

**Codigo:** L-02  
**Foco disciplinar:** Redes de Computadores e Tecnologias Web  
**Formato:** jogo web conduzido pelo professor  
**Tempo sugerido:** 25 a 35 minutos  
**Demo publica:** https://albertomateus9.github.io/packet-rescue-network-quest/

Este projeto transforma uma aula tecnica em uma missao guiada. O professor cria equipes ficticias, inicia cronometro, revela fases, pontua evidencias e exporta um relatorio da aula.

## Dinamica De Aula

- **Find The Local Link ID:** Explain why local link resolution happens before the first frame is sent.
- **Decode The Destination:** Order the DNS, TCP, and HTTP steps correctly.
- **Rescue From Congestion:** Choose whether the likely cause is DNS, link congestion, or server failure using the clues.

## Competencias

- network reasoning
- protocol sequencing
- incident diagnosis
- technical vocabulary

## Como Rodar

Abra `index.html` diretamente ou sirva a pasta:

```bash
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Politica De Dados

- Usa apenas missoes sinteticas e equipes ficticias.
- Guarda estado apenas no `localStorage` do navegador.
- Nao possui login, backend, API externa ou registro real de estudante.

## License

MIT. See [LICENSE](LICENSE).
