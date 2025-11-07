# Opções visuais para o campo "Tipo de ação"

As três variações abaixo já estão prontas no código. Basta escolher a que mais combinar com o seu gosto
mudando o valor da constante `ACTION_BAR_STYLE` (lá no começo do arquivo `RN_BUILDER.py`).

## 1. `sutil` (padrão)
- Faixa levemente mais clara que o resto da tela, com borda fina.
- Mantém tudo alinhado em linha única, então parece parte natural do formulário.
- Ideal para quem quer só um destaque de leve sem chamar atenção demais.

## 2. `faixa`
- Adiciona uma barrinha colorida fininha na lateral esquerda e coloca o conteúdo dentro de um "cartão".
- Gera a sensação de bloco principal, facilitando entender que esse campo controla o resto.
- Continua discreta, porque a cor é suave e combina com o tema.

## 3. `linha`
- Remove o fundo: fica só o texto e uma linha fininha embaixo, igual a uma seção de formulário moderno.
- Combina bem se você prefere telas mais limpas e sem caixas aparentes.
- Mesmo sem caixa, o texto continua alinhado e com boa leitura.

> **Como trocar:** procure pela linha `ACTION_BAR_STYLE = os.environ.get("RN_ACTION_BAR_STYLE", "sutil")` no arquivo
> `RN_BUILDER.py` e troque o nome `"sutil"` por `"faixa"` ou `"linha"`. Se quiser voltar ao padrão, é só deixar `"sutil"` novamente.
