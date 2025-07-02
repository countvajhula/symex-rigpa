.. image:: https://github.com/countvajhula/symex-rigpa/actions/workflows/test.yml/badge.svg
    :target: https://github.com/countvajhula/symex-rigpa/actions

symex-rigpa
===========

Use Symex with Rigpa in Emacs.

Installation
============

symex-rigpa is not on a package archive such as `MELPA <https://melpa.org/>`_ yet, but you can install it using `Straight.el <https://github.com/radian-software/straight.el>`_ (or `Elpaca <https://github.com/progfolio/elpaca>`_) by putting this somewhere in your :code:`.emacs.d`:

.. code-block:: elisp

  (use-package symex-rigpa
    :after (symex rigpa)
    :straight
    (symex-rigpa
     :local-repo "~/.emacs.d/my-packages/symex-rigpa"
     :type git)
    :config
    (symex-rigpa-initialize))

Non-Ownership
=============

This work is not owned by anyone. Please see the `Declaration of Non-Ownership <https://github.com/drym-org/foundation/blob/main/Declaration_of_Non_Ownership.md>`_.
