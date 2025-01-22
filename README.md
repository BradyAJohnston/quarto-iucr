
# <%= title %>

## Creating a New Article

To create a new article using this format:

```bash
quarto use template BradyAJohnston/quarto-iucr
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add BradyAJohnston/quarto-iucr
```

Then, add the format to your document options:

```yaml
format:
  quarto-iucr-pdf: default
```    

## Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

