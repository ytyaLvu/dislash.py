.. currentmodule:: dislash.interactions

Responding to a slash-command
=============================

.. _interaction:

Interaction
-----------

| Obtainable via **async** functions decorated with ``@slash_client.command()`` or ``@slash_commands.command()``
| See :ref:`slash_client`

.. autoclass:: Interaction

    .. automethod:: reply

    .. automethod:: edit

    .. automethod:: delete


.. _interaction_data:

Interaction Data
----------------

.. autoclass:: InteractionData

    .. automethod:: get_option



.. _interaction_data_option:

Interaction Data Option
-----------------------

.. autoclass:: InteractionDataOption

    .. automethod:: get_option
