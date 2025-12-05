The default models used by Qodo Merge dY'Z (October 2025) are a combination of OpenAI GPT-5.1 (primary), OpenAI GPT-5 (fallback), Haiku-4.5, and Gemini 2.5 Pro.

### Selecting a Specific Model

Users can configure Qodo Merge to use only a specific model by editing the [configuration](https://qodo-merge-docs.qodo.ai/usage-guide/configuration_options/) file.
The models supported by Qodo Merge are:

- `openai/gpt-5.1`
- `openai/gpt-5`
- `claude-haiku-4.5`
- `gemini-2.5-pro`
- `o4-mini`
- `deepseek/r1`

To restrict Qodo Merge to using only `o4-mini`, add this setting:

```toml
[config]
model="o4-mini"
```

To restrict Qodo Merge to using only `OpenAI GPT-5.1`, add this setting:

```toml
[config]
model="openai/gpt-5.1"
```

To restrict Qodo Merge to using only `gemini-2.5-pro`, add this setting:

```toml
[config]
model="gemini-2.5-pro"
```

To restrict Qodo Merge to using only `claude-4-sonnet`, add this setting:

```toml
[config]
model="claude-4-sonnet"
```
