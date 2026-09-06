# Imagens Ricciello

Tudo aqui é referenciado por `index.html` (objeto `IMGS`, hero, sobre e a marca).

## Marca
- `logo-completo.png`    -> arte oficial completa (emblema + "Ricciello / Calçados
                            Masculinos"), 500x500 com fundo transparente. É o
                            arquivo-mestre: não é usado pela página, fica aqui para
                            não se perder de novo.
- `logo.webp`            -> só o emblema (cavalo + coroa + arco), recortado do arquivo
                            acima. É o que aparece no header (56px) e no rodapé (40px);
                            o "Ricciello / Calçados Masculinos" ao lado é texto de
                            verdade em HTML, não imagem.
- `favicon.png`          -> ícone da aba: a cabeça do cavalo sobre disco escuro, porque
                            o dourado sozinho some no fundo claro da aba.
- `apple-touch-icon.png` -> 180x180 para "Adicionar à tela de início" no iOS.

Os três derivados saem do `logo-completo.png`. Se a arte oficial mudar, troque o
mestre e gere os recortes de novo.

## Galerias do catálogo (objeto `IMGS`)
- `sabbia-1..3.webp`     -> Sabbia
- `bianco-1..2.webp`     -> Bianco
- `cioccolato-1..3.webp` -> Cioccolato
- `notte-1..3.webp`      -> Notte
- `perla-1..4.webp`      -> Perla
- `venezia-1..4.webp`    -> Venezia

Sem fotos ainda: Nero, Miele e Potenza (entradas vazias em `IMGS`). O card aparece
normalmente; é só adicionar `<modelo>-1.webp` e listar no `IMGS`.

## Outras
- `hero.webp`  -> imagem grande do topo
- `sobre.webp` -> seção Quem Somos
