Cracking nuts & malware analysis
=========================================

Deciphering the inner workings of compiled languages in detail. Disassembling binaries to solve the crackmes at the assembly level.

And inspecting several malware samples in the wild, a typical pattern arises, making analysing other samples easier with
experience. Knowing these common behaviours gives an idea of what to look for on the defensive side.

.. image:: _static/images/in-progress.png
  :alt: Forever in progress ...

----

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: Testlab

   Static analysis <https://testlab.tymyrddin.dev/docs/static/README>
   Disassemblers <https://testlab.tymyrddin.dev/docs/dis/README>
   Debuggers <https://testlab.tymyrddin.dev/docs/deb/README>
   Decompilers <https://testlab.tymyrddin.dev/docs/dec/README>
   Program editing tools <https://testlab.tymyrddin.dev/docs/pet/README>
   Analysis automation programming <https://testlab.tymyrddin.dev/docs/aap/README>
   Software forensic tools <https://testlab.tymyrddin.dev/docs/dfir/README>
   Malware analysis tools <https://testlab.tymyrddin.dev/docs/malware/README>

----

Notes on techniques
-----------------------------

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Cracking

   docs/cracking/README.md
   docs/cracking/assessment.md
   docs/cracking/formats.md
   docs/cracking/linux.md
   docs/cracking/windows.md
   docs/cracking/wasm.md

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

----

Coding for better understanding of concepts, and for some hands-on.

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: Useful snippets

   Using Windows APIs <https://github.com/tymyrddin/codes-reverse/tree/main/windows>
   Code snippets for using WASM <https://github.com/tymyrddin/codes-reverse/tree/main/wasm>

----

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

----

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: More practice

   Malware traffic analysis exercises <https://www.malware-traffic-analysis.net/training-exercises.html>
   theZoo - A Live Malware Repository <https://github.com/ytisf/theZoo>
   crackmes.one <https://crackmes.one/>

----

.. image:: _static/images/books.png
  :alt: Useful books
