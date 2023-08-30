# CSTC40 Keymap

## Introdução
Este é o atual **keymap** que estou usando no meu teclado 40% ortolinear, **CSTC40** da [KPepublic](https://kprepublic.com/products/cstc40-40-rgb-40-hot-swappable-mechanical-keyboard-pcb-programmed-qmk-via-vial-firmware-rgb-switch-underglow-type-c-planck?_pos=2&_psq=cstc&_ss=e&_v=1.0).
Os keymaps anteriores podem ser localizados no diretório **arquivos**.

Infelizmente o **CSTC40** não possui o código fonte disponível oficialmente, sendo necessário usar o softwares VIA e **VIAL**. Sendo este último necessário para abrir o arquivo do keymap para flashear o teclado, disponível aqui com o nome **cstc40_vial.vil**.
<br>
> **Info:**
[itsvar8](https://github.com/itsvar8) conseguiu gerar o código fonte para flashear usando o qmk, ainda não testei e não sei se funciona perfeitamente. Sim, pretendo testar ele, mas ainda não tive tempo. Quem tiver interesse, segue o link do repositório: https://github.com/itsvar8/vial-qmk/tree/cstc40/keyboards/kprepublic/cstc40


Por conveniência, uso o padrão ABNT2, que não é suportado nativamente pelo qmk. Fiz algumas adaptações para conseguir usar de forma aceitável o teclado em ANSI e ISO mas com o sistema operacional em ABNT2. Segue a **tabela de conversão das teclas**:

 ABNT  | ANSI | ISO  | QMKcode
:-----:|:----:|:----:|:-------:
| ç    | ; :  |      | KC_SCOLON
| ~ ^  | ' "  |      | KC_QUOTE
| ' "  | ~ `  |      | KC_GRAVE
| ´ `  | [ {  |      | KC_LBRACKET
| ; :  | / ?  |      | KC_SLASH
| / ?  |      | \ _  | KC_RO
| \ \| |      | \ \| | KC_NONUS_BSLASH
| [ {  | ] }  |      | KC_RBRACKET
| ] }  | \ \| |      | KC_BSLASH

<br>A seguir apresento o esquema gráfico do keymap.

![Esquema atual cstc40](https://github.com/FredericoFavaro/cstc40_layout/blob/main/esquemas/CSTC40_layout.png?raw=true "Esquema atual CSTC40")

> **Info:** Esse esquema foi feito no [draw.io](https://www.drawio.com/),
caso queira usar e editar, [clique aqui!](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=CSTC40.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1h03ayhXwjO0dLhyLY32HAu7QaUWtHD9_%26export%3Ddownload)
