:mod:`cle` --- Binary Loader
============================

.. automodule:: cle


Loading Interface
-----------------

.. automodule:: cle.loader


Backends
--------

.. automodule:: cle.backends
.. automodule:: cle.backends.externs
.. automodule:: cle.backends.symbol
.. automodule:: cle.backends.regions
.. automodule:: cle.backends.elf.elf
.. automodule:: cle.backends.elf.elfcore
.. automodule:: cle.backends.elf.metaelf
.. automodule:: cle.backends.elf.symbol
.. automodule:: cle.backends.elf.regions
.. automodule:: cle.backends.elf.hashtable
.. automodule:: cle.backends.pe.pe
.. automodule:: cle.backends.pe.symbol
.. automodule:: cle.backends.pe.regions
.. automodule:: cle.backends.macho.macho
.. automodule:: cle.backends.macho.symbol
.. automodule:: cle.backends.macho.section
.. automodule:: cle.backends.macho.segment
.. automodule:: cle.backends.macho.binding
.. automodule:: cle.backends.cgc.cgc
.. automodule:: cle.backends.cgc.backedcgc
.. automodule:: cle.backends.hex
.. automodule:: cle.backends.blob
.. automodule:: cle.backends.idabin


Relocations
-----------

CLE's loader implements program relocation data on a plugin basis.
If you would like to add more relocation implementations, do so by subclassing the ``Relocation`` class and overriding any relevant methods or properties.
Put your subclasses in a module in the ``relocations`` package.
The name of the subclass will be used to determine when to use it!
Look at the existing versions for details.

.. automodule:: cle.backends.relocations
.. automodule:: cle.backends.pe.reloc


Thread-local storage
--------------------

.. automodule:: cle.backends.tls
.. automodule:: cle.backends.tls.elf_tls
.. automodule:: cle.backends.tls.pe_tls


Misc. Utilities
---------------

.. automodule:: cle.gdb
.. automodule:: cle.memory
.. automodule:: cle.patched_stream
.. automodule:: cle.address_translator
.. automodule:: cle.utils


Errors
------

.. automodule:: cle.errors
