<br><br>

<h1 align="center">Clip</h1>

<p align="center">
  <a href="/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg"/></a>
  <a href="https://goreportcard.com/report/github.com/mingrammer/clip"><img src="https://goreportcard.com/badge/github.com/mingrammer/clip"/></a>
</p>

<p align="center">

A simple key-value store for clipboard

</p>

<br><br><br>

# Installation

```bash
go get github.com/mingrammer/clip
```

Or using [Homebrew](https://brew.sh)

```bash
brew tap mingrammer/clip https://github.com/mingrammer/clip.git
brew install clip
```

# Usage

```bash
# List all key-value pairs
clip list

# Get a value of a specific key
clip get <key>

# Set a key-value pair
clip set <key> <value>

# Delete a key
clip del <key>

# Copy a value of a specific key to clipboard
clip cp <key>
```

# License

Deatils on [LICENSE](/LICENSE)