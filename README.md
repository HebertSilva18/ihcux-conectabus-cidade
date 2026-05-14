# ConectaBus — Prototipo de Baixa Fidelidade

**Disciplina:** Interacao Humano-Computador e UX  
**Repositorio:** ihcux-conectabus-cidade  
**Cidade:** Contagem - MG

---

## Nome do Aluno

- Herbert Silva

---

## Contexto de Uso

O usuario esta na rua, em movimento, provavelmente segurando mochila ou sacola. Ele precisa descobrir rapidamente como chegar ao trabalho na Av. das Industrias, em Contagem - MG, sem perder o onibus. O aplicativo foi pensado para uso com apenas um polegar, com o minimo de passos possivel e informacoes claras mesmo sob sol forte ou com pressa.

---

## Telas do Prototipo

O prototipo foi criado no Miro e contem 5 telas principais:

1. **Tela 1 - Busca de Rota:** campo de busca com destinos frequentes de Contagem (Casa, Trabalho, Hospital Municipal). Botao grande para facilitar o toque rapido com o polegar.
2. **Tela 2 - Resultado de Rotas:** tres opcoes de rota (Mais Rapido, Mais Barato e Bicicleta) com o tempo de chegada em destaque, maior do que o numero da linha.
3. **Tela 3 - Mapa de Percurso:** representacao simples do trajeto com pontos A e B, linha de rota e icone do onibus em movimento.
4. **Tela 4 - Carteira Digital:** saldo em destaque no topo, QR Code centralizado para validacao na catraca e historico das ultimas viagens.
5. **Tela 5 - Detalhes do Veiculo:** barra visual de lotacao, informacoes de acessibilidade (rampa, ar-condicionado, audio e espaco para cadeirante), proximas paradas e botao de SOS.

---

## Decisoes de UX

- O **tempo de chegada** (exemplo: 22 min) esta sempre com fonte maior do que o numero da linha, porque o usuario precisa saber se vai chegar a tempo, nao memorizar o numero da linha.
- Os **destinos frequentes** aparecem logo abaixo do campo de busca para evitar que o usuario precise digitar toda vez.
- As **tres opcoes de rota** usam rotulos simples e diretos (Mais Rapido, Mais Barato e Bicicleta) para facilitar a decisao sem exigir comparacao de numeros.
- O **QR Code** ocupa a area central da Tela 4 porque e a acao principal da carteira, facilitando a leitura pela catraca.
- O botao **SOS** esta visivel em todas as telas na barra de navegacao inferior, garantindo acesso rapido em situacoes de emergencia.

---

## Acessibilidade

- Botoes com altura minima de 44px para uso com polegar ou para pessoas com mobilidade reduzida.
- Rampa de acesso, audio de anuncio de paradas e espaco para cadeirante aparecem com destaque na Tela 5.
- A barra visual de lotacao permite entender a situacao do onibus sem precisar ler texto.
- Contraste alto em preto e branco para facilitar a leitura em ambientes externos e com incidencia de sol.
- Navegacao simples com quatro botoes fixos na base da tela, sem necessidade de gestos complexos.

---

## Estrutura do Repositorio

```
/prototipo
  sobre-prototipo.md
README.md
```


