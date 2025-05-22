# BatalhaNaval
Este projeto é a versão avançada do jogo *Batalha Naval*, com a adição de *habilidades especiais com áreas de efeito*: Cone, Cruz e Octaedro. Cada habilidade pode ser usada para afetar partes do tabuleiro estrategicamente.

---

 Funcionalidades

- Tabuleiro 10x10 representando água e navios.
- Três habilidades especiais:
Cone – Área expandida em forma triangular.
Cruz – Afeta linha e coluna central.
Octaedro – Afeta células em forma de losango.
Matrizes de habilidades dinâmicas, com valores `1` para células afetadas e `0` para não afetadas.
Sobreposição das habilidades no tabuleiro com base em um ponto de origem.
 
---
 Como Executar?

1. Compile o programa:
   ```bash
   gcc batalha_naval_mestre.c -o batalha
