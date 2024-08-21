# json-key-sync - JSON Resource Key Transformer
This project is a simple tool that transforms the key-value pairs in a JSON file for multilingual resources from the structure `"key": "value"` to `"key": "key"`. This can be useful in specific scenarios during multilingual resource management.

## Key Features
- Converts all values in a JSON file to their corresponding keys.
- Simplifies multilingual resource management.
- Easy to use.

## Example

### Input Example (Original JSON)
```json
{
    "label.a": "this is a",
    "label.b": "this is b"
}
```

### Output Example (Transformed JSON)
```json
{
    "label.a": "label.a",
    "label.b": "label.b"
}
```

## Usage
https://yueseo.github.io/json-key-sync/
