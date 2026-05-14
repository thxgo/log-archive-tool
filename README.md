# log-archive

A lightweight CLI tool that compresses directories into `.tar.gz` archives with an auto-generated timestamp.

## Installation

1. Make the script executable:

```bash
chmod +x log-archive
```

2. Create the local bin directory if you haven't already:

```bash
mkdir ~/.local/bin/
```

3. Move it to your local bin so you can run it from anywhere:

```bash
cp log-archive ~/.local/bin/
```

## Usage

```bash
log-archive [directory]
```

## Example

```bash
log-archive /var/log/
```
