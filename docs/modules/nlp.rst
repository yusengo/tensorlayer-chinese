API - 自然语言处理
======================

自然语言处理与词向量。

.. automodule:: tensorlayer.nlp

.. autosummary::

   generate_skip_gram_batch

   sample
   sample_top

   simple_read_words
   read_words
   read_analogies_file
   build_vocab
   build_reverse_dictionary
   build_words_dataset
   words_to_word_ids
   word_ids_to_words
   save_vocab

   basic_tokenizer
   create_vocabulary
   initialize_vocabulary
   sentence_to_token_ids
   data_to_token_ids


训练嵌入矩阵的迭代函数
------------------------------

.. autofunction:: generate_skip_gram_batch


抽样方法
-------------------

.. autofunction:: sample
.. autofunction:: sample_top


词的向量表示 
-------------------------------

从文件中读取文本
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: simple_read_words
.. autofunction:: read_words

从文件中读取类比题目
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: read_analogies_file

建立词汇表、文本与ID转换字典及文本ID化
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: build_vocab
.. autofunction:: build_reverse_dictionary
.. autofunction:: build_words_dataset

文本转ID，ID转本文
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: words_to_word_ids
.. autofunction:: word_ids_to_words

保存词汇表
^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: save_vocab

机器翻译相关函数
---------------------------

本文ID化
^^^^^^^^^^^^^^^^

.. autofunction:: basic_tokenizer

建立或读取词汇表
^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: create_vocabulary
.. autofunction:: initialize_vocabulary

文本转ID，ID转本文
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: sentence_to_token_ids
.. autofunction:: data_to_token_ids
