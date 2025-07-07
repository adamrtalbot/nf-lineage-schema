# Nextflow Lineage Schema

## ⚠️ Disclaimer

This is an **unofficial schema** for the Nextflow lineage feature.

- It is built manually by me
- It is **not supported** in any way, shape, or form
- Use at your own risk

## Contributing

Please feel free to:

- Open issues for bugs, questions, or suggestions
- Submit pull requests for improvements
- Help make this schema better for the community

## Schema

The main schema file is `nextflow-lineage-v1beta1-schema.json` which defines the structure for Nextflow lineage data.

## Usage

You can use the schema with any system that supports JSON schema version 2020-12. See the [JSON schema documents for more tools](https://json-schema.org/tools) which can use this schema file.

As an example, I have built documentation for the schema using [@adobe/jsonschema2md](https://github.com/adobe/jsonschema2md) which can be found in the [`docs`](./docs/README.md) directory. This also writes the `out/nextflow-lineage-v1beta1-schema.json` file which is parsed by the docs tool.
