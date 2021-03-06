.. meta::
   :description: Use hasura seeds apply to apply seed data
   :keywords: hasura, docs, CLI, hasura seeds apply

.. _hasura_seed_apply:

Hasura CLI: hasura seed apply
-----------------------------

Apply seed data.

Synopsis
~~~~~~~~


Apply seed data.

::

  hasura seed apply [flags]

Examples
~~~~~~~~

::

    # Apply all seeds on the database:
    hasura seed apply

    # Apply only a particular file:
    hasura seed apply --file seeds/1234_add_some_seed_data.sql

Options
~~~~~~~

::

  -f, --file stringArray   seed file to apply
  -h, --help               help for apply

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --admin-secret string            admin secret for Hasura GraphQL engine (env "HASURA_GRAPHQL_ADMIN_SECRET")
      --certificate-authority string   path to a cert file for the certificate authority (env "HASURA_GRAPHQL_CERTIFICATE_AUTHORITY")
      --database string                database on which operation should be applied
      --endpoint string                http(s) endpoint for Hasura GraphQL engine (env "HASURA_GRAPHQL_ENDPOINT")
      --envfile string                 .env filename to load ENV vars from (default ".env")
      --insecure-skip-tls-verify       skip TLS verification and disable cert checking (default: false) (env "HASURA_GRAPHQL_INSECURE_SKIP_TLS_VERIFY")
      --log-level string               log level (DEBUG, INFO, WARN, ERROR, FATAL) (default "INFO")
      --no-color                       do not colorize output (default: false)
      --project string                 directory where commands are executed (default: current dir)
      --skip-update-check              skip automatic update check on command execution

SEE ALSO
~~~~~~~~

* :ref:`hasura seed <hasura_seed>` 	 - Manage seed data

*Auto generated by spf13/cobra*
