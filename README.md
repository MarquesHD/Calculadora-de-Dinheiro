# Contador de Caixa - Sistema para Fechamento de Caixa

Um sistema simples e eficiente para fechamento de caixa e contagem de dinheiro, desenvolvido em HTML puro com foco na agilidade operacional do dia a dia de estabelecimentos comerciais.

---

## Sobre o Projeto

Este aplicativo foi criado para facilitar a contagem de cédulas e moedas durante o fechamento de caixa. Com uma interface limpa e objetiva, ele permite:

- Inserir a quantidade de cada nota e moeda
- Visualizar o subtotal por denominação
- Calcular automaticamente o valor total em espécie
- Zerar todos os campos com um clique
- Imprimir o resumo para conferência ou arquivamento

Ideal para lojas, restaurantes, padarias, quiosques e qualquer negócio que trabalhe com dinheiro físico.

---

## Funcionalidades

| Funcionalidade | Descrição |
|----------------|-----------|
| Contador por denominação | Suporte para cédulas de R$ 200, 100, 50, 20, 10, 5 e moedas de R$ 1, 0,50, 0,25, 0,10, 0,05, 0,01 |
| Subtotal automático | Cada linha exibe o valor parcial daquela denominação |
| Cálculo do total | Soma de todos os valores em Reais (BRL) |
| Resumo detalhado | Lista final com quantidade × valor para cada item |
| Botão "Zerar" | Limpa todos os campos instantaneamente |
| Botão "Imprimir" | Gera uma versão impressa do fechamento |

---

## Tecnologias Utilizadas

- **HTML5** – Estrutura da página
- **CSS3** – Estilização leve e responsiva
- **JavaScript (Vanilla)** – Cálculos e interatividade

> Nenhuma dependência externa ou frameworks – pronto para uso offline.

---

## Como Executar

1. Baixe o arquivo `index.html`
2. Abra diretamente no seu navegador (Chrome, Edge, Firefox, etc.)
3. Preencha as quantidades e veja os resultados em tempo real
4. Clique em **Zerar** para limpar ou **Imprimir** para salvar em papel/PDF

---

## Exemplo de Saída
Contador de Dinheiro - Uso Interno
Cédulas e Moedas
R
200
C
E
ˊ
D
U
L
A
→
S
u
b
t
o
t
a
l
:
3
→
R
200C 
E
ˊ
 DULA→Subtotal:3→R 600,00
R
100
C
E
ˊ
D
U
L
A
→
S
u
b
t
o
t
a
l
:
5
→
R
100C 
E
ˊ
 DULA→Subtotal:5→R 500,00
R
50
C
E
ˊ
D
U
L
A
→
S
u
b
t
o
t
a
l
:
1
→
R
50C 
E
ˊ
 DULA→Subtotal:1→R 50,00
R
20
C
E
ˊ
D
U
L
A
→
S
u
b
t
o
t
a
l
:
0
→
R
20C 
E
ˊ
 DULA→Subtotal:0→R 0,00
R
10
C
E
ˊ
D
U
L
A
→
S
u
b
t
o
t
a
l
:
0
→
R
10C 
E
ˊ
 DULA→Subtotal:0→R 0,00
R
5
C
E
ˊ
D
U
L
A
→
S
u
b
t
o
t
a
l
:
2
→
R
5C 
E
ˊ
 DULA→Subtotal:2→R 10,00
R
1
M
O
E
D
A
→
S
u
b
t
o
t
a
l
:
38
→
R
1MOEDA→Subtotal:38→R 76,00
R
0
,
50
M
O
E
D
A
→
S
u
b
t
o
t
a
l
:
45
→
R
0,50MOEDA→Subtotal:45→R 22,50
R
0
,
25
M
O
E
D
A
→
S
u
b
t
o
t
a
l
:
14
→
R
0,25MOEDA→Subtotal:14→R 3,50
R
0
,
10
M
O
E
D
A
→
S
u
b
t
o
t
a
l
:
7
→
R
0,10MOEDA→Subtotal:7→R 0,70
R
0
,
05
M
O
E
D
A
→
S
u
b
t
o
t
a
l
:
98
→
R
0,05MOEDA→Subtotal:98→R 4,90
R
0
,
01
M
O
E
D
A
→
S
u
b
t
o
t
a
l
:
0
→
R
0,01MOEDA→Subtotal:0→R 0,00

VALOR TOTAL
R$ 1.312,60

text

---

## Melhorias Futuras (Sugestões)

- [ ] Salvar histórico de fechamentos
- [ ] Exportar para CSV/Excel
- [ ] Suporte para múltiplos caixas/usuários
- [ ] Tema escuro
- [ ] Atalhos de teclado para agilizar a contagem

---

## Licença

Este projeto é de uso interno e livre para adaptações. Sinta-se à vontade para modificar e melhorar conforme sua necessidade.

---

## Autor

Desenvolvido para simplificar a rotina de operações de caixa. Para dúvidas ou sugestões, entre em contato.

---

**Feito com** ☕ e dedicação.
