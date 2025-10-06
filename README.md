# RADIUSS 

Welcome to the web home of RADIUSS! Here we maintain:

- a website with information about radiuss
- automated pipelines to update and render plots for RADIUSS projects

This repo was archived in October 6, 2025. See https://computing.llnl.gov/projects/radiuss for current information.

## Usage

### Data

We run a [nightly action](.github/workflows/update-data.yaml) to get updated data
for RADIUSS projects, however you can generate the same data on your own using
[Contributor CI](https://contributor-ci.readthedocs.io/en/latest/getting_started/user-guide.html) as follows!

```bash
# Export a GitHub token to the environment
export GITHUB_TOKEN=xxxxxxxxxxx

# install contributor-ci
pip install contributor-ci

# check out the extractors available!
# cci list
```

The tool will read in repos from [contributor-ci.yaml](contributor-ci.yaml) (default) and we store data for cci in [_data](_data),
so to run an extractor you can do the following. Note that we want to cache data monthly so we use `--save-format year/month` instead of the
default of `year/month/day`

```bash
$ cci --out-dir _data extract --save-format year/month <extractor>
```

And the ones we do for the site (a subset) are:

```bash
$ cci --out-dir _data extract --save-format year/month repos repo_metadata topics languages releases stars activity_commits activity_lines
```

### Api

The site data is served from a set of static APIs!

 - `/radiuss/api/languages.json`
 - `/radiuss/api/releases.json`
 - `/radiuss/api/repos.json`
 - `/radiuss/api/repos-metadata.json`
 - `/radiuss/api/stars.json`
 - `/radiuss/api/topics.json`
 - `/radiuss/api/commits.json`
 - `/radiuss/api/lines.json`


### Custom Data

#### Avatars

If you want to define a custom avatar image for a project:

1. Add the image to [assets/img/custom/avatars](assets/img/custom/avatars)
2. Add _just the name_ to [_data/custom.yaml](_data/custom.yaml) under avatars.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)
file for details

All new contributions must be made under the MIT License.

See [LICENSE](https://github.com/LLNL/radiuss-ci/blob/master/LICENSE),
[COPYRIGHT](https://github.com/LLNL/radiuss-ci/blob/master/COPYRIGHT), and
[NOTICE](https://github.com/LLNL/radiuss-ci/blob/master/NOTICE) for details.

SPDX-License-Identifier: (MIT)

LLNL-CODE-793462
