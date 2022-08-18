A repo for testing out the ability of tsdate to date ancient genomes of unknown time.

Currently the pipelines take advantage of functionality in branches of the tsinfer and
tsdate repos, so you should install those specific branches like this

python3.9 -m pip install git+http://github.com/tskit-dev/tsinfer@refs/pull/687/merge
python3.9 -m pip install git+http://github.com/tskit-dev/tsdate@ancient_samples

