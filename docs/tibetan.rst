Tibetan
*******
Classical Tibetan refers to the language of any text written in Tibetic after the Old Tibetan period; though it extends from the 7th century until the modern day, it particularly refers to the language of early canonical texts translated from other languages, especially Sanskrit. The phonology implied by Classical Tibetan orthography is basically identical to the phonology of Old Tibetan, but the grammar varies greatly depending on period and geographic origin of the author. Such variation is an under-researched topic. 
Source: `Wikipedia 
<https://en.wikipedia.org/wiki/Classical_Tibetan>`_.

Corpora
=======

Use ``CorpusImporter()`` or browse the `CLTK GitHub repository <https://github.com/cltk>`_ (anything beginning with ``tibetan_``) to discover available Tibetan corpora.

.. code-block:: python

   In [1]: from cltk.corpus.utils.importer import CorpusImporter

   In [2]: c = CorpusImporter('tibetan')

   In [3]: c.list_corpora
   Out[3]: ['tibetan_pos_tdc', 'tibetan_lexica_tdc']

