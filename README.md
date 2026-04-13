# Extract plain text from HTML

## Installation

```
$ uv add plainhtml
```

For development in this repository:

```
$ uv sync --dev
```

## Example

```python
>>> import plainhtml
>>> html = "<html><body><p>foo</p><p>bar</p></body></html>"
>>> plainhtml.extract_text(html)
'foo\n\nbar'
```
