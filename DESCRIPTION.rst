This package includes the Snowpipe python SDK

Snowflake Documentation is available at:
https://docs.snowflake.net/

Source code is also available at: https://github.com/snowflakedb/snowflake-ingest-python

Release Notes
-------------------------------------------------------------------------------

- v1.0.5 (November 04, 2022)

      - Pin dependency package to newer versions (requests, snowflake-connector-python)
      - Fix pyJwt logic to allow for version >= 2.0.0
      
- v1.0.4 (May 11, 2021)

      - Support a special account name style.

- v1.0.3 (January 11, 2021)

      - Use older version of pyJwt by pinning the version(<2.0.0)

- v1.0.2 (March 09, 2020)

      - Stop logging JWT token

- v1.0.1 (November 08, 2019)

      - Replaced Botocore's vendored requests with standalone requests

- v1.0.0 (September 19, 2018)

      - Fix typing package issue in python 3.5.0 and 3.5.1
      - Support key rotation in key pair authentication

- v0.9.1 (November 9, 2017)

      - Public preview release
