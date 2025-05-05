# Pint Setup

A Bash script to automate the setup of [Laravel Pint](https://laravel.com/docs/12.x/pint) with a custom configuration file.

## Requirements

- PHP with Composer installed
- Bash
- A `.env` file in the same directory as the script with the following (replace with a link to your custom `pint.json` file):
```env
PINT_CONFIG_URL=https://raw.githubusercontent.com/mikeycodingstuff/pint-config/main/pint.json
```
> Replace the URL with a link to your custom `pint.json` file

## Usage

1. Add the script and a `.env` file together in any directory.
2. Set `PINT_CONFIG_URL` to your configuration file link.
3. Add the script to your PATH.
4. Run `pint-setup` from any Composer project.

## After Setup

Run Pint in your project:
```sh
./vendor/bin/pint
```
Customize `pint.json` as needed.
See [Laravel Pint docs](https://laravel.com/docs/12.x/pint#configuring-pint).
