# ConectaBus — Prototipo de Baixa Fidelidade

**Disciplina:** Interação Humano-Computador & UX  
**Repositório:** ihcux-conectabus-cidade  
**Cidade:** Contagem - MG

---

## Nome dos Alunos

- Hebert Silva

---

## Contexto de Uso

O usuario esta na rua, em movimento, provavelmente segurando mochila ou sacola. Ele precisa descobrir rapidamente como chegar ao trabalho na Av. das Industrias, em Contagem - MG, sem perder o onibus. O aplicativo foi pensado para uso com apenas um polegar, com o minimo de passos possivel e informacoes claras mesmo sob sol forte ou pressa.

---

## Telas do Prototipo

O prototipo foi criado no Miro e contem 5 telas principais:

1. **Tela 1 - Busca de Rota:** campo de busca com destinos frequentes de Contagem (Casa, Trabalho, Hospital Municipal). Botao grande para facilitar o toque rapido.
2. **Tela 2 - Resultado de Rotas:** tres opcoes de rota (Mais Rapido / Mais Barato / Bicicleta) com tempo de chegada em destaque maior que o numero da linha.
3. **Tela 3 - Mapa de Percurso:** representacao simples do trajeto com pontos A e B, linha de rota e icone do onibus em movimento.
4. **Tela 4 - Carteira Digital:** saldo em destaque, QR Code centralizado para validacao na catraca e historico de viagens.
5. **Tela 5 - Detalhes do Veiculo:** barra visual de lotacao, grid de acessibilidade (rampa, ar-condicionado, audio, cadeirante), proximas paradas e botao SOS.

---

## Decisoes de UX

- O **tempo de chegada** (ex: "22 min") esta sempre com fonte maior que o numero da linha, porque o usuario precisa saber se vai chegar a tempo, nao memorizar o numero.
- Os **destinos frequentes** aparecem logo abaixo do campo de busca para evitar que o usuario precise digitar toda vez.
- As **3 opcoes de rota** usam rotulos claros (Mais Rapido / Mais Barato / Bicicleta) para facilitar a decisao sem exigir comparacao de numeros.
- O **QR Code** ocupa o centro da Tela 4 porque e a acao principal da carteira.
- O botao **SOS** esta visivel em todas as telas na barra de navegacao inferior.

---

## Acessibilidade

- Botoes com altura minima de 44px para uso com polegar ou mobilidade reduzida.
- Rampa, audio de anuncio de paradas e espaco para cadeirante aparecem com destaque na Tela 5.
- Barra visual de lotacao permite entender a situacao sem precisar ler texto.
- Contraste alto (preto e branco) para facilitar leitura em ambientes externos e com sol.
- Navegacao simples com 4 botoes fixos na base da tela.

---

## Estrutura do Repositorio

```
/prototipo
  prototipo.png
  prototipo.pdf
README.md
```

---

## Link do Prototipo no Miro

[Acessar o board no Miro](https://miro.com/app/board/uXjVHTXBd8Y=/)
