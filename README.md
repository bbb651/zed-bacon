# Zed Bacon

## Recommended Config
```json
{
    "languages": {
        "Rust": {
            "language_servers": ["bacon", "rust-analyzer", "..."]
        }
    },
    "lsp": {
        "rust-analyzer": {
            "initialization_options": {
                "diagnostics": { "enable": false },
                "checkOnSave": { "enable": false }
            }
        }
    }
}
```
