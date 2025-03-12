[![CI](https://github.com/ryanwi/hiringtrends/actions/workflows/ci.yml/badge.svg)](https://github.com/ryanwi/hiringtrends/actions/workflows/ci.yml)
[![codecov](https://codecov.io/github/ryanwi/hiringtrends/graph/badge.svg?token=NrwAqEaIwm)](https://codecov.io/github/ryanwi/hiringtrends)

# Hacker News (HN) Hiring Trends

A Ruby program for analyzing software technology trends from Hacker News whoishiring posts.
Created by <a href="https://www.ryanwilliams.dev">Ryan Williams</a>
(<a href="https://twitter.com/ryanwi">@ryanwi</a>)

## To do

* [x] Use updated dictionary file
* [ ] Constrain single-item functionality so that running the program for Feb 2025 does not process Mar 2025
* [ ] Update RSS and subscription links
* [ ] Update branding and authorship
* [ ] Update README with new authorship and better setup/usage instructions
* [ ] Move data files to S3
* [ ] Generate index page automatically
* [ ] Automatically fetch up to latest hiring post
* [ ] Skip fetching existing data
* [ ] Limit data to last 10 years, archive old posts
* [ ] Figure out if terms parser works on word boundaries or substrings (e.g. "infra/ops" vs. "infra ops")
* [ ] Remove all dictionary terms that have had no matches in the last 5 years
* [ ] Implement dynamic dictionary file
  * [ ] Write script to extract terms from hiring posts
  * [ ] Save terms to local dictionary file
  * [ ] Use local dictionary file
* [ ] Implement automatic charts for total post trends, top languages and other tech
* [ ] Write LLM-generated summary for MoM and YoY trends
* [ ] Modernize design

## Warnings/Disclaimer

This is a personal development project.  You are welcome to use, modify, etc. and I welcome any feedback or questions.

## Requirements

  * Ruby (3.3+)

## Usage

From the command line, launch the program's console with the following command:

```
bin/hiringtrends
```

To launch an interactive console

```
bin/console
```

In the console, run the program with the following command:

```
hn = run_program(item_id)
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Author

**Ryan Williams**

- <https://www.ryanwilliams.dev>
- <https://github.com/ryanwi>
- <https://hachyderm.io/@ryanwi>
- <https://twitter.com/ryanwi>
