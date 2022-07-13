# elastic-clis

Simple CLIs can be used from CLI/cron to help managing/monitoring an elasticsearch clusters.

Some utilities are expecting to find 'jq' (https://stedolan.github.io/jq/) in $PATH otherwise it mostly dependent upon standard POSIX.1 utilities.

Login credentials are expected to be found in ~/.netrc for curl (-n) to use in a line format like:

    machine FQDN login ESLUSERNAME password ESPASSWORD

I know these ought to saved in a keystore for non-readability :)
