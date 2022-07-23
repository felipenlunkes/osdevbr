<p align='center'>
<a href="https://github.com/felipenlunkes/osdevbr"><img height="250" src="https://github.com/felipenlunkes/osdevbr/blob/main/img/header.gif"></a>&nbsp;&nbsp;
</p>

# Um pouco sobre a inicialização

Após a inicialização do firmware, o [BIOS](https://pt.wikipedia.org/wiki/BIOS) ou outro firmware, como [UEFI](https://pt.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface) em modo legado, realiza a busca de um volume/disco marcado como inicializável e, ao encontrar, carrega o primeiro setor para o endereço 0x7C00.