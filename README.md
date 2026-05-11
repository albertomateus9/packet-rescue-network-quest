# Resgate do Pacote: Missão de Redes

Jogo de redes em que equipes conduzem um pacote por ARP, DNS, TCP, HTTP, latência e falhas simuladas.

> Projeto educacional inspirado na EETEPA Vilhena Alves. Não é sistema oficial institucional e não usa dados reais de estudantes.

## Visão Geral

**Código:** L-02  
**Foco disciplinar:** Redes de Computadores e Tecnologias Web  
**Formato:** jogo web conduzido pelo professor  
**Tempo sugerido:** 25 a 35 minutos  
**Demonstração pública:** https://albertomateus9.github.io/packet-rescue-network-quest/

Este projeto transforma uma aula técnica em uma experiência de jogo educacional. A fantasia central é: Resgate de um pacote atravessando enlaces, protocolos e gargalos até chegar ao serviço.

## Como Conduzir A Dinâmica

- **Verbo de jogo:** liberar portões de protocolo.
- **Mecânica:** A equipe só avança o pacote quando explica o protocolo correto e identifica o risco da fase.
- **Papel da equipe:** Use o caminho do pacote como trilha: cada equipe precisa abrir o próximo portão com uma justificativa.
- **Recompensa da rodada:** Pacote liberado.
- **Registro final:** exporte o relatório para guardar pontuação, evidências e próximos passos.

## Roteiro Do Professor

- **Objetivo:** Fazer a turma explicar o caminho de um pacote usando pistas e decisões por equipe.
- **Preparação:** Revise rapidamente ARP, DNS, TCP e HTTP antes da rodada.
- **Condução:** A cada fase, peça que a equipe diga qual camada está atuando e qual risco existe.
- **Fechamento:** Compare os caminhos escolhidos e destaque como pequenos erros afetam todo o fluxo.
- **Critérios:** use a rubrica do app para pontuar evidência, colaboração, comunicação e melhoria.

## Missões

- **Encontrar o Próximo Salto (6 min):** Explicar por que a resolução local acontece antes do primeiro quadro ser enviado. Evidência: Uma explicação sobre ARP e um risco caso a resposta esteja errada.
- **Decifrar o Destino (7 min):** Ordenar corretamente as etapas DNS, TCP e HTTP. Evidência: Cadeia de protocolos ordenada.
- **Escapar do Congestionamento (8 min):** Escolher se a causa provável é DNS, congestionamento de enlace ou falha no servidor usando as pistas. Evidência: Diagnóstico e ação de mitigação.

## Competências

- raciocínio de redes
- sequência de protocolos
- diagnóstico de incidentes
- vocabulário técnico

## Como Rodar

Abra `index.html` diretamente ou sirva a pasta:

```bash
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Política De Dados

- Usa apenas missões sintéticas e equipes fictícias.
- Guarda estado apenas no `localStorage` do navegador.
- Não possui login, servidor, API externa ou registro real de estudante.

## Licença

MIT. Consulte [LICENSE](LICENSE).
