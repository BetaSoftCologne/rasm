<img src="assets/logo.png" alt="Logo courtesy of Barjack" title="logo">

## Rasm Z80 assembler
    
Rasm was designed to be damn FAST and handle HUGE projects. On a modern machine, it can assemble millions of instructions in a blink of an eye. It's almost 30 times faster than the best alternatives. 

## Integrated crunched sections

- Rasm know how to load&crunch on the fly files when doing INCBIN (including binaries)
- Rasm is able to assemble and crunch portions of code, and relocate following instructions
- Rasm can assemble as much code as you want and break the 64K barrier before crunch
- Many crunchers are supported: LZ4, LZ48, LZ49, ZX0, ZX7, Exomizer 2, AP-Ultra, LZSA1, LZSA2

## Native format

- CPC cartridge
- CPC snapshots up to 4M
- CPC EDSK (as many as you want in update or generation mode)
- CPC/ZX TAPE output
- CPC/ZX Binaries with or without AMSDOS/HOBETA header
- ZX snapshots
- you can initialize memory with a snapshot or a cartridge (usefull to patch memory)

## Debug output

- symbols import, or export in files, CPC snapshot
- breakpoint export in CPC snapshot or files
- dependencies export

## Mostly unlimited design

- ORG checking, unlimited memory workspaces where labels are shared, bank management, structures
- conditionnal macro, unlimited & embeded loops with local labels, switch/case
- floating point engine, mathematical functions, ...
- crunched segments declaration may overflow the 64K limit as much as you want

## Compatibility for archeology (with old versions of these assemblers)

- MAXAM
- AS80
- UZ80
- Pasmo

## Oldschool is beautiful

- Amsdos real & Microsoft basic 40bits float support

## Documentation

There is a cool French and English documentation, you should read it ;)

- EN: http://rasm.wikidot.com/english-index:home
- FR: http://rasm.wikidot.com/

## History

The project was born a few years ago (2017) because i needed a really fast assembler in order to finish my demo before the deadline of the Alchemy 2017. The project was quite huge with approx 350.000 words to assemble but thanks to rasm, the 512K cartridge compiled in a blink of an eye even on my slow Atom CPU. Now Rasm is the reference for huge projects and ultra-fast assembling.

## Links

BTW there is many other assemblers you could try:

- ORGAMS http://orgams.wikidot.com/ (definitely the best native Z80 assembler on any machine)
- VASM http://sun.hasenbraten.de/vasm/
- SJASM http://xl2s.tk/
- SJASMPlus https://github.com/sjasmplus/sjasmplus
- UZ80 http://cngsoft.no-ip.org/uz80.htm
- PASMO https://pasmo.speccy.org/

