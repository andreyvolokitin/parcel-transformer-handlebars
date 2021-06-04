# @andreyvolokitin/parcel-transformer-handlebars

Transform handlebars templates to HTML

## Installation
```
npm install -D @andreyvolokitin/parcel-transformer-handlebars
```

## Usage
Add it to your `.parcelrc`:

```
{
  "extends": ["@parcel/config-default"],
  "transformers": {
    "*.hbs": ["@andreyvolokitin/parcel-transformer-handlebars"],
  },
}
```