# Carta Super Trunfo - Primeiro desafio em C

## Descrição do Projeto 📂
O **Carta Super Trunfo** é um projeto em linguagem C que simula um jogo de batalha entre cartas de cidades. Cada carta possui atributos como população, área, PIB, número de pontos turísticos, densidade populacional, PIB per capita e um **Super Poder** calculado a partir desses atributos.  

O objetivo do jogo é comparar duas cartas e determinar a vencedora de cada atributo, seguindo regras específicas de comparação. O projeto foi desenvolvido em diferentes níveis de complexidade, do iniciante ao Mestre.

---

## Funcionalidades por Nível

### Nível Novato
- Cadastro de cartas com atributos básicos: estado, código, nome da cidade, população, área, PIB e número de pontos turísticos.
- Exibição dos dados cadastrados de cada carta.

### Nível Intermediário
- Cálculo da **densidade populacional**: população ÷ área.
- Cálculo do **PIB per capita**: PIB total ÷ população.
- Exibição desses atributos junto aos dados da carta.

### Nível Mestre
- Cálculo do **Super Poder**: soma de todos os atributos numéricos da carta, incluindo o inverso da densidade populacional (quanto menor a densidade, maior o poder).  
- Comparação de duas cartas atributo por atributo:  
  - **Densidade populacional:** vence a carta com menor valor.  
  - **Demais atributos e Super Poder:** vence a carta com maior valor.  
- Exibição clara de qual carta venceu em cada categoria, usando `1` para Carta 1 e `0` para Carta 2.

---

## Tecnologias Utilizadas
- Linguagem C
- Compilador C padrão (como GCC)

---



## Como Executar 📥 
```bash
Clone o repositório >
git clone https://github.com/anacris-muniz/cartas-super-trunfo.git

Acesse a pasta >
cd cartas-super-trunfo

Compile o código >
gcc main.c -o cartas-super-trunfo
 
Execute o programa >

./cartas-super-trunfo   # Linux/Mac
cartas-super-trunfo.exe # Windows




