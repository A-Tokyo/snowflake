# Snowflake

Snowflake is Medium's tool for planning and supporting our engineers' career development. You can read more
about how we use this tool in our [growth framework documentation](https://medium.com/s/engineering-growth-framework).
Our growth tool is hosted [publicly](https://snowflake.medium.com).

At Thndr we used this tool as a starting point and extended it to align with our career development framework

## Contributions

You are free to use, change and build on this work to make it useful for your organization. We will happily consider
unencumbered code contributions to improve functionality, but as this is the actual tool we use within Thndr, acceptance is likely to be intentional, and deliberate. Meaning, slow. As such, you may prefer to fork the codebase for your own needs. We will not accept any contributions that modify the text of the application (but, thank you in advance for pointing out any typos).

## Installation

Get yarn if you don’t have it already:

`npm install -g yarn`

Install dependencies:

`yarn`

### Running the dev server

`yarn dev`

### Building

`yarn export`

This will put a static version of the site in `out/`.

## Future work

- Load initial data from a file, to improve flexibility.
- Add restricted job title selection and validation.
