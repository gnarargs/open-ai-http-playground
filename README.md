# LLM Playground

HTTP examples for various OpenAI APIs.

## Responses API

See [responses.http](responses.http).

TODO:
- Add example that uses `instructions` to pass role in one request but does not follow through on next request when using previous reponses id.

## Tools

See [tools.http](tools.http).

## Structured Outputs

See [structured_outputs.http](structured_outputs.http).

Notes:
- Using JSON Schema, all fields must be required and `additionalPropeties` must be false
