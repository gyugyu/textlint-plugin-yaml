# textlint-plugin-yaml
for yaml style resource supoprt for textlint

## Installation

```
npm install -g textlint-plugin-yaml@npm:@gyugyu/textlint-plugin-yaml
```

## Usage

add plugin to your ``.textlintrc``

```
{
  "plugins": [
    "yaml"
  ]
}
```

execute textlint

```
textlint config/locales/**/*.yml
```

## Build

```
npm install
babel -s -d lib src
```
