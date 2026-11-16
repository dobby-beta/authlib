Fixed
~~~~~

- An expired token from the ``password`` grant without a refresh token is
  fetched again when ``username`` and ``password`` are given in
  ``access_token_params``. It used to raise ``InvalidTokenError``.
