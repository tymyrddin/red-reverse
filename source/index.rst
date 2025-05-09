Cracking nuts & malware analysis
=========================================

Deciphering the inner workings of compiled languages in detail. Disassembling binaries to solve crackmes at the assembly level, using as basic tools as possible.

And inspecting several malware samples in the wild, a typical pattern arises, making analysing other samples easier with experience. Knowing these common behaviours gives an idea of what to look for on the defensive side.

.. image:: _static/images/in-progress.png
  :alt: Forever in progress ...

----

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: Tools @Testlab

   Static analysis <https://testlab.tymyrddin.dev/docs/static/README>
   Disassemblers <https://testlab.tymyrddin.dev/docs/dis/README>
   Debuggers <https://testlab.tymyrddin.dev/docs/deb/README>
   Decompilers <https://testlab.tymyrddin.dev/docs/dec/README>
   Program editing tools <https://testlab.tymyrddin.dev/docs/pet/README>
   Analysis automation programming <https://testlab.tymyrddin.dev/docs/aap/README>
   Software forensic tools <https://testlab.tymyrddin.dev/docs/dfir/README>
   Malware analysis tools <https://testlab.tymyrddin.dev/docs/malware/README>
   Binary analysis VM <https://testlab.tymyrddin.dev/docs/vm/ba>

----

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Binary formats

   docs/binary/README.md
   docs/binary/anatomy.md
   docs/binary/elf.md
   docs/binary/pe.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Cracking

   docs/cracking/README.md
   docs/cracking/assessment.md
   docs/cracking/linux.md
   docs/cracking/windows.md
   docs/cracking/wasm.md


.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: RE applications @GitHub

   macOS Reverse Engineering framework <https://github.com/tymyrddin/codes-reverse/blob/main/reveng-mac-apps>
   Windows Reverse Engineering framework <https://github.com/tymyrddin/codes-reverse/blob/main/reveng-windows-apps>
   Linux Reverse Engineering framework <https://github.com/tymyrddin/codes-reverse/blob/main/reveng-linux-apps>
   Code snippets for using WASM <https://github.com/tymyrddin/codes-reverse/blob/main/wasm/README.md>

----

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Malware analysis

   docs/malware/README.md
   docs/malware/history.md
   docs/malware/behaviours.md
   docs/malware/purpose.md
   docs/malware/signatures.md
   docs/malware/analysis.md
   docs/malware/packers.md

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: Malware analysis code @GitHub

   Memory analysis <https://github.com/tymyrddin/codes-reverse/blob/main/memory-analyser/README.md>
   Virtual function reverse engineering tool <https://github.com/tymyrddin/codes-reverse/blob/main/vtable_analyser/README.md>
   Analysing Anti-Reverse engineering tricks <https://github.com/tymyrddin/codes-reverse/blob/main/anti_re_analyser/README.md>
   PE/ELF header parser <https://github.com/tymyrddin/codes-reverse/blob/main/pe-elf-header-parser/README.md>
   Dynamic analysis for API monitoring <https://github.com/tymyrddin/codes-reverse/blob/main/dynamic-analysis-api/README.md>

----

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Root-me cracking challenges

   docs/root-me/README.md
   docs/root-me/elf-x86-0.md
   docs/root-me/elf-x86-basic.md
   docs/root-me/pe-x86-0.md
   docs/root-me/elf-cpp-0.md
   docs/root-me/godot-0.md
   docs/root-me/pe-dotnet-0.md
   docs/root-me/elf-mips-basic.md
   docs/root-me/elf-x64-go-basic.md
   docs/root-me/elf-x86-fake.md
   docs/root-me/elf-x86-ptrace.md
   docs/root-me/godot-bytecode.md
   docs/root-me/wasm-intro.md
   docs/root-me/elf-arm-basic.md
   docs/root-me/godot-mono.md
   docs/root-me/pyc-bytecode.md
   docs/root-me/elf-x86-no-br.md
   docs/root-me/elf-arm-1337.md
   docs/root-me/elf-x86-crackpass.md
   docs/root-me/elf-x86-exploitme.md
   docs/root-me/elf-x86-random.md
   docs/root-me/gb-basic.md
   docs/root-me/apk-anti-debug.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: TryHackMe rooms

   docs/thm/README.md
   docs/thm/pdfs.md
   docs/thm/macros.md
   docs/thm/bags.md
   docs/thm/matter.md

----

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: More practice

   Malware traffic analysis exercises <https://www.malware-traffic-analysis.net/training-exercises.html>
   theZoo - A Live Malware Repository <https://github.com/ytisf/theZoo>
   crackmes.one <https://crackmes.one/>

----

Books
---------------------------

.. card-carousel:: 3

    .. card::
        :link: https://nostarch.com/binaryanalysis

        .. image:: _static/images/bookcovers/practical-binary-analysis.png

    .. card::
        :link: https://link.springer.com/book/10.1007/978-1-4842-9153-5

        .. image:: _static/images/bookcovers/foundations-linux-debugging-disassembling-reversing.png

    .. card::
        :link: https://www.packtpub.com/product/mastering-reverse-engineering/9781788838849

        .. image:: _static/images/bookcovers/mastering-reverse-engineering.png

    .. card::
        :link: https://nostarch.com/rootkits

        .. image:: _static/images/bookcovers/rootkits-bootkits.png

    .. card::
        :link: https://nostarch.com/malware

        .. image:: _static/images/bookcovers/practical-malware-analysis.png

    .. card::
        :link: https://www.packtpub.com/product/mobile-app-reverse-engineering/9781801073394

        .. image:: _static/images/bookcovers/mobile-app-reverse-engineering.png
