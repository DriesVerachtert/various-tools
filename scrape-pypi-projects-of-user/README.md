A small script which I needed to extract the list of projects of a pypi user by parsing that user's public page.
It also fetches the download stats of each of the pypi packages if they're available.

For example: https://pypi.org/user/bbp.opensource/

=> you get a list of projects like blueetl, bluepyemodel, ...

The result is stored in a CSV and in a PostgreSQL database
