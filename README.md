# Quimicar

**O átomo por dentro, elemento por elemento** — ferramenta web (um único arquivo HTML) para estudar os 118 elementos químicos pelo **modelo de Bohr**, entender **passo a passo** como os elementos se unem em ligações **iônicas, covalentes e metálicas** **balancear equações químicas** e resolver **pilhas eletroquímicas** — tudo no formato de exercício resolvido: enunciado, resolução passo a passo e resposta destacada.

Criado por **Prof. Me. Rodrigo Gonçalves (Prof Oswy)** · 📺 [youtube.com/@ProfOswy](https://www.youtube.com/@ProfOswy)

---

## Recursos

### Aba Elementos químicos

- **Tabela periódica clicável** com as 10 classificações por cor (metais alcalinos, alcalino-terrosos, de transição, outros metais, semimetais, não metais, halogênios, gases nobres, lantanídeos e actinídeos).
- **Modelo de Bohr animado**, com elétrons girando nas camadas K a Q. O núcleo mostra prótons e nêutrons como bolinhas e, nos átomos grandes, como números.
- **Resumo do átomo**: prótons, nêutrons, elétrons e camadas, com uma frase explicando o papel de cada partícula (prótons definem o elemento, elétrons fazem as ligações, nêutrons definem o isótopo).
- **Onde aparece e para que serve**, com exemplos brasileiros quando existem (nióbio de Araxá, bauxita, Angra, césio-137 de Goiânia).
- **Diagrama de Linus Pauling** com o preenchimento dos subníveis, a camada de valência e o subnível mais energético destacados, e aviso das exceções (Cr, Cu, Pd, Au…).
- **Ligações típicas** de cada elemento, com exemplos de compostos.
- **Exercício resolvido** de cada elemento: prótons, nêutrons e elétrons; distribuição por camadas; camada de valência e período; íon mais provável — cada item com o botão *Ver resolução*.
- **Caixinhas explicativas** em termos como *isótopo* e *camada de valência*.

### Aba Ligações químicas

- Escolha **dois elementos** (ou um dos exemplos prontos) e o Quimicar identifica o tipo de ligação.
- **Passo a passo** revelado um de cada vez: tipo dos elementos, camada de valência (notação de Lewis), transferência ou compartilhamento de elétrons, equilíbrio de cargas e resultado.
- **Iônica**: regra do cruzamento de cargas, fórmula e nome do composto (ex.: Al₂O₃, óxido de alumínio; Fe₂O₃, óxido de ferro(III)).
- **Covalente**: número de ligações de cada átomo, pares compartilhados e fórmula estrutural com ligações simples, duplas e triplas.
- **Metálica**: cátions no retículo e mar de elétrons, com o nome da liga quando conhecida (latão, bronze, nitinol…).
- Elétrons de cada elemento em cores diferentes, para mostrar de onde cada um veio.

### Aba Balanceamento

- Digite qualquer equação (ex.: `Fe + O2 -> Fe2O3`) ou escolha um dos 19 exemplos, de combustões a reações da construção civil (calcinação do calcário, hidratação e carbonatação da cal, coagulação no tratamento de água).
- **Tente você**: ajuste os coeficientes com + e − e acompanhe a contagem de átomos de cada elemento, com aviso quando a equação fica balanceada ou pode ser simplificada.
- **Resolução pelo método algébrico**, revelada passo a passo: contagem de átomos, uma letra por coeficiente, sistema de equações por elemento, resolução, MMC para chegar a inteiros e conferência final.
- Aceita parênteses (`Ca(OH)2`), hidratos (`CuSO4·5H2O`) e avisa quando a fórmula tem erro ou a equação não pode ser balanceada.
- Lembretes da Lei de Lavoisier, da ordem MACHO e de que os índices não podem ser alterados.

### Aba Pilhas

- Escolha dois metais (Mg, Al, Zn, Cr, Fe, Ni, Sn, Pb, Cu, Ag, Au) ou toque na tabela de potenciais-padrão de redução.
- O exercício é montado com os dados de E° e resolvido em 7 passos: comparação dos potenciais, ânodo e cátodo, semirreações, igualdade de elétrons (MMC), reação global, ddp (ΔE° = E°cátodo − E°ânodo) e resposta.
- **Esquema da pilha** com eletrodos, soluções, ponte salina, voltímetro com a ddp e o fluxo de elétrons animado; notação da pilha (ex.: Zn | Zn²⁺ ‖ Cu²⁺ | Cu).
- Aplicações ligadas à engenharia quando o par é conhecido: galvanização, ânodo de sacrifício, corrosão galvânica aço–cobre, emendas alumínio–cobre, folha de flandres, pilha de Daniell.

### Geral

- Abre sempre no **modo claro**; o **modo escuro** é opcional, pelo botão no topo.
- Funciona no computador e no celular.

## Como usar

1. Abra o `index.html` no navegador.
2. Na aba **Elementos químicos**, clique em um elemento da tabela para ver o átomo; use ← → para navegar e as abas abaixo do modelo para ver a distribuição eletrônica e as ligações.
3. Na aba **Ligações químicas**, escolha dois elementos e avance com **Próximo passo** ou clique em **Mostrar tudo**.
4. Na aba **Balanceamento**, digite ou escolha uma equação, tente balancear com os botões + e − e confira a resolução passo a passo.
5. Na aba **Pilhas**, escolha os dois metais e avance pela resolução até a resposta com o esquema da pilha.

## Executando / hospedando

- **Local:** basta abrir o `index.html` — não há instalação nem dependências, além das fontes IBM Plex Sans, IBM Plex Mono e Kalam, carregadas via Google Fonts.
- **GitHub Pages:** mantenha o arquivo principal como `index.html`, faça o commit e ative o Pages em *Settings → Pages* (branch `main`). O link ficará em `https://profoswy.github.io/Quimicar/`.

## Observações

- O número de nêutrons corresponde ao isótopo mais abundante na natureza ou, nos elementos radioativos, ao mais estável (massa entre colchetes).
- A distribuição por camadas no modelo de Bohr segue as configurações eletrônicas reais, com as exceções; o diagrama de Pauling mostra a previsão pela ordem de energia. Acima do Z = 103, os valores são apenas previstos.
- Nos metais de transição, a ligação iônica usa a carga mais comum do íon.
- Os potenciais-padrão de redução são valores tabelados usuais (25 °C, 1 mol/L); livros diferentes podem trazer pequenas variações na segunda casa decimal.
- É uma ferramenta didática, com modelos simplificados (Bohr, regra do octeto). Confira sempre os conteúdos com a bibliografia da disciplina.

## Licença

Todos os direitos reservados — veja [LICENSE.md](LICENSE.md). Uso pessoal, acadêmico e educacional é permitido; redistribuição, modificação, remoção de créditos e uso comercial exigem autorização do autor.

© 2026 Prof. Me. Rodrigo Gonçalves (Prof Oswy)
