---
title: Home
layout: home
date_fmt: "%B %d, %Y"
---
### Welcome to SFZFormat.com!

This is the main reference point for anyone who wants to create virtual musical
instruments using the SFZ format. Currently the SFZ 2 opcodes and ARIA extensions
documented though some require more detail, and SFZ 2 opcodes not supported by
ARIA still need to be added. There's enough information to make complex SFZ
insturments already, but we'll continue to add more.

To make use of the SFZ format requires three things:

- Samples
- [SFZ player](/software/players)
- SFZ file

which tells the player how to use the samples. The SFZ file itself can be created
using any text editor, though for more complex cases with hundreds or thousands
of samples, additional tools can make this easier - some people use spreadsheets,
and there are also dedicated [SFZ creation tools](/software/tools).

The SFZ format is a file format to define how a collection of samples are
arranged for performance. The goal behind the SFZ format is to provide a free,
simple, minimalistic and expandable format to arrange, distribute and use audio
samples with the highest possible quality and the highest possible performance
flexibility. Soundware, software and hardware developers can create, use and
distribute the SFZ format files for free, for either free or commercial applications. 

- Here's a [basic SFZ file](/tutorials/basic_sfz_file) you can copy to start your own
- Here is the [list of SFZ headers](/headers/)
- The [list of SFZ 1](/opcodes/sfz_1/) can be found here.
- You can browse the many SFZ 2 opcodes [starting here](/opcodes/sfz_2/).
- A few opcodes have been added to [ARIA / Sforzando](/extensions/aria/opcodes/)
    for more flexibility

### SFZ Programming Video Tutorials

Here are a couple of videos to help you get started with SFZ

- [SFZ Tutorial Part 1](https://youtu.be/bTFs524KrGc):
  Hello World! by David Viens

- [SFZ Tutorial Part 2](https://youtu.be/iWIRegt32o0):
  Generators, transpose and ADSR by David Viens

### Making Instruments

Text guides on how to make a simple instrument, covering the essential opcodes

- [Drum basics](/tutorials/drum_basics) - covers `global`, `group` and
  `region` headers, `sample`, `key`, `lovel` / `hivel`, `amp_velcurve_N`,
  `seq_length`, `seq_position` and `lorand` / `hirand`.

- [Sustained note basics](/tutorials/sustained_note_basics) - using a flute
  as an example.
  Adds `lokey` / `hikey`, `pitch_keycenter`, `xfin` / `xfout`, `locc` / `hicc`,
  `keyswitching`, `group`, `off_by` and `off_mode`.

Some more advanced topics

- [Vibrato](/tutorials/vibrato) - currently describes basic bowed string vibrato,
  will be expanded later to include other instruments and also filter wobble.

- [Legato](/tutorials/legato) - currently simple glides, will be expanded later
  to include true sampled legato.

- [Cymbal muting](/tutorials/cymbal_muting) - using `group`, `off_by`, `off_mode`
  and `polyphony` to make hi-hat and cymbal notes mute previous notes
  in a musically useful way.

### Other Online Resources

- [The SFZ forum](https://www.plogue.com/plgfrms/viewforum.php?f=14) on Plogue.com
- [The old rgc:audio SFZ file format page](/legacy), online for posterity.
- [Peter L. Jones' SFZ page and drum mappings](http://www.drealm.info/sfz/).

# Latest News

{% include post.html %}